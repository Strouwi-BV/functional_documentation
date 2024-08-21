

# Klanten

<primary-label ref="client_projectmanagement_primary"/>
## Klantenoverzicht

<include from="lib.topic" element-id="overview">
    <var name="overview_name" value="klantenoverzicht"/>
    <var name="item_singular" value="klant"/>
    <var name="item_plural" value="klanten"/>
    <var name="new_item" value="nieuwe klant"/>
    <var name="table_information" value="de naam, het aantal projecten en de status"/>
    <var name="detail_anchor" value="klant-detail"/>
    <var name="new_anchor" value="klant-aanmaken"/>
    <var name="new_img" value="ClientOverviewNewHighlighted.png"/>
    <var name="filter_button_img" value="ClientOverviewFilterHighlighted.png"/>
    <var name="filter_img" value="ClientOverviewFilterActiveSelected.png"/>
    <var name="detail_img" value="ClientOverviewDetailHighlighted.png"/>
</include>

## Klant aanmaken

<procedure>
    <step>
        Ga direct naar <a href="%url_buildbase%/clients/create"/>.<br/>
        Of klik op <shortcut>Nieuwe klant</shortcut> in het <a anchor="klantenoverzicht">klantenoverzicht</a>.
        <img src="ClientOverviewNewHighlighted.png"  alt="Klantenoverzicht met nieuwe klant aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <warning>Het is niet mogelijk om een naam meerdere keren te gebruiken.</warning>
        <img src="ClientCreateFilledSaveHighlighted.png"  alt="Klant aanmaken ingevuld met opslaan aangeduid"/>
    </step>
    <step>
        U wordt nu terug doorverwezen naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
</procedure>

## Klant detail

Op de detailpagina van een klant kan u alle informatie van de klant bekijken en bewerken.

### Kop

De kop heeft verschillende eigenschappen:
- [Klantnaam](#klantnaam)
- Terugkeren naar klantenoverzicht
- [Status van de klant](#status)
- [Acties](#acties)

#### Klantnaam

Hier kan u de naam van de klant bekijken en [wijzigen](#klantnaam-aanpassen).

#### Terugkeren naar klantenoverzicht

Wanneer u op deze link klikt, wordt u teruggestuurd naar het [klantenoverzicht](#klantenoverzicht).

#### Status

Een klant kan één van twee statussen hebben: actief en inactief.
<img src="ClientDetailHeaderActiveHighlighted.png"  alt="Klantenoverzicht met actief aangeduid"/>
<img src="ClientDetailHeaderInactiveHighlighted.png"  alt="Klantenoverzicht met inactief aangeduid"/>

#### Acties

U kan enkele acties uitvoeren op een klant:
- [De status wijzigen](#status-aanpassen)
- [De klant verwijderen](#verwijderen)

<img src="ClientDetailHeaderActionsHighlighted.png" alt="Klantdetail met acties aangeduid"/>

### Klant informatie

U ziet hier de algemene informatie over de klant zoals de start- en einddatum, het btw-nummer en het adres. 
Wanneer een adres is toegevoegd wordt dit ook weergegeven op een [Google Maps](https://www.google.be/maps) kaart.
Het is ook mogelijk om deze gegevens te [wijzigen](#klant-informatie-aanpassen).
<img src="ClientDetailClientInformationHighlighted.png" alt="Klantdetail met klant informatie aangeduid"/>

### Contactinformatie

Dit zijn contactgegevens van de klant zoals de naam en de functie van de contactpersoon, een telefoonnummer en een e-mailadres.
Het is ook mogelijk om deze gegevens te [wijzigen](#contactinformatie-aanpassen).
<img src="ClientDetailContactInformationHighlighted.png" alt="Klantdetail met contactinformatie aangeduid"/>

### Projecten

Hier vindt u een [projectenoverzicht](Projecten.md#projectenoverzicht) van alle projecten van deze klant.
<img src="ClientDetailProjectsHighlighted.png" alt="Klantdetail met projecten aangeduid"/>

U kan vanuit deze pagina ook een nieuw project maken.

## Klant aanpassen

### Klantnaam aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast de klantnaam.
        <img src="ClientDetailNameEditHighlighted.png" alt="Klantdetail met klantnaam aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe naam in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ClientEditClientNameFilledSaveHighlighted.png" alt="Klantnaam aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Status aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="ClientDetailHeaderActionsHighlighted.png" alt="Klantdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Zet op inactief</shortcut> of op <shortcut>Zet op actief</shortcut>.
        <list columns="2">
            <li>
                <img src="ClientDetailActionsSetInactiveHighlighted.png" alt="Klantdetail met op inactief zetten aangeduid"/>
            </li>
            <li>
                <img src="ClientDetailActionsSetActiveHighlighted.png" alt="Klantdetail met op actief zetten aangeduid"/>
            </li>
        </list>
    </step>
</procedure>

### Verwijderen

<procedure>
    <step>
        Ga naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="ClientDetailHeaderActionsHighlighted.png" alt="Klantdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Verwijder</shortcut>.
        <img src="ClientDetailActionsDeleteHighlighted.png" alt="Klantdetail met op verwijderen aangeduid"/>
    </step>
</procedure>

### Klant informatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de klant informatie kader.
        <img src="ClientDetailClientInformationEditHighlighted.png" alt="Klantdetail met klant informatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ClientEditClientInformationFilledSaveHighlighted.png" alt="Klant informatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Contactinformatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="klant-detail">detailpagina van de klant</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de contactinformatie kader.
        <img src="ClientDetailContactInformationEditHighlighted.png" alt="Klantdetail met contactinformatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ClientEditContactInformationFilledSaveHighlighted.png" alt="Klant contactinformatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>