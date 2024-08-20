# Werknemers

<primary-label ref="employee_management_primary"/>
## Werknemersoverzicht

<include from="lib.topic" element-id="overview">
    <var name="overview_name" value="werknemersoverzicht"/>
    <var name="item_singular" value="werknemer"/>
    <var name="item_plural" value="werknemers"/>
    <var name="new_item" value="nieuwe werknemer"/>
    <var name="table_information" value="de naam, email, functie, teams en de status"/>
    <var name="detail_anchor" value="werknemer-detail"/>
    <var name="new_anchor" value="werknemer-aanmaken"/>
    <var name="new_img" value="EmployeeOverviewNewHighlighted.png"/>
    <var name="filter_button_img" value="EmployeeOverviewFilterHighlighted.png"/>
    <var name="filter_img" value="EmployeeOverviewFilterActiveSelected.png"/>
    <var name="detail_img" value="EmployeeOverviewDetailHighlighted.png"/>
</include>

## Werknemer aanmaken

<procedure>
    <step>
        Ga direct naar <a href="%url_buildbase%/users/create"/>.<br/>
        Of klik op <shortcut>Nieuwe werknemer</shortcut> in het <a anchor="werknemersoverzicht">Werknemersoverzicht</a>.
        <img src="EmployeeOverviewNewHighlighted.png"  alt="Werknemersoverzicht met nieuwe werknemer aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeCreateFilledSaveHighlighted.png"  alt="Werknemer aanmaken ingevuld met opslaan aangeduid"/>
    </step>
    <step>
        U wordt nu terug doorverwezen naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
</procedure>

## Werknemer detail

Op de detailpagina van een werknemer kan u alle informatie van de werknemer bekijken en bewerken.

### Kop

De kop heeft verschillende eigenschappen:
- [Werknemersnaam](#werknemersnaam)
- [Functie](#functie)
- [Statuut](#statuut)
- [Terugkeren naar werknemersoverzicht](#terugkeren-naar-werknemersoverzicht)
- [Status van de werknemer](#status)
- [Acties](#acties)

#### Werknemersnaam

Hier kan u de naam van de werknemer bekijken en [wijzigen](#werknemersnaam-aanpassen).

#### Functie

Hier kan u de functie van de werknemer bekijken en [wijzigen](#functie-aanpassen).

#### Statuut

Hier kan u het statuut van de werknemer bekijken en [wijzigen](#statuut-aanpassen).

#### Terugkeren naar werknemersoverzicht

Wanneer u op deze link klikt, wordt u teruggestuurd naar het [werknemersoverzicht](#werknemersoverzicht).

#### Status

Een werknemer kan één van twee statussen hebben: actief en inactief.
<img src="WerknemerDetailHeaderActiveHighlighted.png"  alt="Werknemerdetail met actief aangeduid"/>
<img src="employeeDetailHeaderInactiveHighlighted.png"  alt="Werknemerdetail met inactief aangeduid"/>

#### Acties

U kan enkele acties uitvoeren op een werknemer:
- [Uren registreren](#uren-registreren)
- [De status wijzigen](#status-aanpassen)
- [Het wachtwoord wijzigen](#wachtwoord-aanpassen)
- [De rol wijzigen](#rol-aanpassen)

<img src="ClientDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>

### Persoonlijke informatie

U ziet hier de algemene informatie over de werknemer zoals de geboortedatum, nationaliteit, rijksregisternummer enz... .
Het is ook mogelijk om deze gegevens te [wijzigen](#persoonlijke-informatie-aanpassen).
<img src="EmployeeDetailPersonalInformationHighlighted.png" alt="Werknemerdetail met persoonlijke informatie aangeduid"/>

### Contactinformatie

Dit zijn contactgegevens van de werknemer zoals het adres, werk email, telefoonnummer, contact voor noodgevallen en een persoonlijk e-mailadres.
Het is ook mogelijk om deze gegevens te [wijzigen](#contactinformatie-aanpassen).
<img src="EmployeeDetailContactInformationHighlighted.png" alt="Werknemerdetail met contactinformatie aangeduid"/>

### Werkrooster

Hier vindt u het werkrooster van de werknemer.
Het is ook mogelijk om deze gegevens te [wijzigen](#werkrooster-aanpassen).
<img src="EmployeeDetailWorkscheduleHighlighted.png" alt="Werknemerdetail met werkrooster aangeduid"/>

## Werknemer aanpassen

### Werknemersnaam aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast de werknemernaam.
        <img src="EmployeeDetailNameEditHighlighted.png" alt="Werknemerdetail met werknemernaam aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe naam in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeEditNameFilledSaveHighlighted.png" alt="Werknemernaam aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Functie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast de functie.
        <img src="EmployeeDetailFunctionEditHighlighted.png" alt="Werknemerdetail met functie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe functie in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeEditFunctionFilledSaveHighlighted.png" alt="functie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Statuut aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast statuut.
        <img src="EmployeeDetailStatuteEditHighlighted.png" alt="Werknemerdetail met statuut aanpassen aangeduid"/>
    </step>
    <step>
        Kies een statuut en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeEditStatuteFilledSaveHighlighted.png" alt="statuut aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Status aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="EmployeeDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Zet op inactief</shortcut> of op <shortcut>Zet op actief</shortcut>.
        <list columns="2">
            <li>
                <img src="EmployeeDetailActionsSetInactiveHighlighted.png" alt="Werknemerdetail met op inactief zetten aangeduid"/>
            </li>
            <li>
                <img src="EmployeeDetailActionsSetActiveHighlighted.png" alt="Werknemerdetail met op actief zetten aangeduid"/>
            </li>
        </list>
    </step>
</procedure>

### Wachtwoord aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="EmployeeDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Wijzig wachtwoord</shortcut>.
        <img src="EmployeeDetailActionsChangePasswordHighlighted.png" alt="Werknemerdetail met Wijzig wachtwoord aangeduid"/>
    </step>
    <step>
        Wijzig het wachtwoord en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeDetailAmendPasswordFilledSaveHighlighted.png" alt="Bewerk wachtwoord met opslaan aangeduid"/>
    </step>    
</procedure>

### Rol aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="EmployeeDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Rol wijzigen </shortcut>.
        <img src="EmployeeDetailActionsChangeRolHighlighted.png" alt="Werknemerdetail met Rol wijzigen aangeduid"/>
    </step>
    <step>
        Selecteer de gewenste rollen en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeDetailAmendRolFilledSaveHighlighted.png" alt="Pas rol aan met opslaan aangeduid"/>
    </step>    
</procedure>



### Persoonlijke informatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de Persoonlijke informatie kader.
        <img src="EmployeeDetailPersonalInformationEditHighlighted.png" alt="Werknemerdetail met Persoonlijke informatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeEditPersonalInformationFilledSaveHighlighted.png" alt="Persoonlijke informatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Contactinformatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de contactinformatie kader.
        <img src="EmployeeDetailContactInformationEditHighlighted.png" alt="Werknemerdetail met contactinformatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeDetailContactInformationFilledSaveHighlighted.png" alt="Werknemer contactinformatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Werkrooster aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de Werkrooster kader.
        <img src="EmployeeDetailWorkscheduleEditHighlighted.png" alt="Werknemerdetail met werkrooster aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="EmployeeDetailWorkscheduleFilledSaveHighlighted.png" alt="Werknemer werkrooster aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

## Uren registreren

<procedure>
    <step>
        Ga naar de <a anchor="werknemer-detail">detailpagina van de werknemer</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="EmployeeDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Registreer uren</shortcut>.
        <img src="EmployeeDetailActionsRegisterHoursHighlighted.png" alt="Werknemerdetail met op inactief zetten aangeduid"/>
        U ziet nu de kalenderpagina van de werknemer, waar u de uren kan registeren.
        <img src="EmployeeDetailActionsRegisterHoursCalendar.png" alt="Kalender van werknemer"/>
        Meer informatie over het registreren van uren vind u <a href="Tijd-registreren.md">hier</a>.
    </step>
</procedure>