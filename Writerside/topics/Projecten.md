# Projecten

## Projectenoverzicht

<include from="lib.topic" element-id="overview">
    <var name="overview_name" value="projectenoverzicht"/>
    <var name="item_singular" value="project"/>
    <var name="item_plural" value="projecten"/>
    <var name="new_item" value="nieuw project"/>
    <var name="table_information" value="de naam, tot welke klant het behoort en de status"/>
    <var name="detail_anchor" value="project-detail"/>
    <var name="new_anchor" value="project-aanmaken"/>
    <var name="new_img" value="ProjectOverviewNewHighlighted.png"/>
    <var name="filter_button_img" value="ProjectOverviewFilterHighlighted.png"/>
    <var name="filter_img" value="ProjectOverviewFilterActiveSelected.png"/>
    <var name="detail_img" value="ProjectOverviewDetailHighlighted.png"/>
</include>

## Project aanmaken

<procedure>
    <step>
        Ga direct naar <a href="%url_buildbase%/projects/create"/>.<br/>
        Of klik op <shortcut>Nieuwe project</shortcut> in het <a anchor="projectenoverzicht">Projectenoverzicht</a>.
        <img src="ProjectOverviewNewHighlighted.png"  alt="Projectenoverzicht met nieuw project aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <warning>Het is niet mogelijk om een projectnaam meerdere keren te gebruiken.</warning>
        <img src="ProjectCreateFilledSaveHighlighted.png"  alt="Project aanmaken ingevuld met opslaan aangeduid"/>
    </step>
    <step>
        U wordt nu terug doorverwezen naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
</procedure>

## Project detail

Op de detailpagina van een project kan u alle informatie van het project bekijken en bewerken.

### Kop

De kop heeft verschillende eigenschappen:
- [Projectnaam](#projectnaam)
- Terugkeren naar projectenoverzicht
- [Status van het project](#status)
- [Acties](#acties)

#### Projectnaam

Hier kan u de naam van het project bekijken en [wijzigen](#projectnaam-aanpassen).

#### Terugkeren naar projectenoverzicht

Wanneer u op deze link klikt, wordt u teruggestuurd naar het [projectenoverzicht](#projectenoverzicht).

#### Status

Een project kan één van twee statussen hebben: actief en inactief.
<img src="ProjectDetailHeaderActiveHighlighted.png"  alt="Projectoverzicht met actief aangeduid"/>
<img src="ProjectDetailHeaderInactiveHighlighted.png"  alt="Projectoverzicht met inactief aangeduid"/>

#### Acties

U kan enkele acties uitvoeren op een project:
- [De status wijzigen](#status-aanpassen)
- [Project verwijderen](#verwijderen)

<img src="ProjectDetailHeaderActionsHighlighted.png" alt="Projectdetail met acties aangeduid"/>

### Project informatie

U ziet hier de algemene informatie over het project zoals de start- en einddatum, 'aangifte van werken' en het adres.
Wanneer een adres is toegevoegd wordt dit ook weergegeven op een [Google Maps](https://www.google.be/maps) kaart.
Het is ook mogelijk om deze gegevens te [wijzigen](#project-informatie-aanpassen).
<img src="ProjectDetailProjectInformationHighlighted.png" alt="Projectdetail met projectinformatie aangeduid"/>

### Contactinformatie

Dit zijn contactgegevens van het project zoals de naam en de functie van de contactpersoon, een telefoonnummer en een e-mailadres.
Het is ook mogelijk om deze gegevens te [wijzigen](#contactinformatie-aanpassen).
<img src="ProjectDetailContactInformationHighlight.png" alt="Projectdetail met contactinformatie aangeduid"/>

### Project foto's

Hier kan u de afbeeldingen van het project vinden.
Het is ook mogelijk om deze afbeeldingen te [wijzigen](#project-foto-s-aanpassen).
<img src="ProjectDetailProjectFotosHighlighted.png" alt="Projectdetail met contactinformatie aangeduid"/>

## Project aanpassen

### Projectnaam aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast de klantnaam.
        <img src="ProjectDetailNameEditHighlighted.png" alt="Klantdetail met klantnaam aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe naam in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ProjectEditProjectNamedFilledSaveHighlighted.png" alt="Klantnaam aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Klant aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op het potlood icoontje naast de klantnaam.
        <img src="ProjectDetailClientEditHighlighted.png" alt="Projectdetail met klant aanpassen aangeduid"/>
    </step>
    <step>
        Kies een klant en klik op <shortcut>Opslaan</shortcut>.
        <img src="ProjectChooseClientSaveHighlighted.png" alt="Klant aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Status aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="ProjectDetailHeaderActionsHighlighted.png" alt="Klantdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Zet op inactief</shortcut> of op <shortcut>Zet op actief</shortcut>.
        <list columns="2">
            <li>
                <img src="ProjectDetailActionsSetInactiveHighlighted.png" alt="Projectdetail met op inactief zetten aangeduid"/>
            </li>
            <li>
                <img src="ProjectDetailActionsSetActiveHighlighted.png" alt="Projectdetail met op actief zetten aangeduid"/>
            </li>
        </list>
    </step>
</procedure>

### Verwijderen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="ProjectDetailHeaderActionsHighlighted.png" alt="Projectdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Verwijder</shortcut>.
        <img src="ProjectDetailActionsDeleteHighlighted.png" alt="Klantdetail met op verwijderen aangeduid"/>
    </step>
</procedure>

### Project informatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de project informatie kader.
        <img src="ProjectDetailProjectInformationEditHighlighted.png" alt="Projectdetail met project informatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ProjectEditProjectInformationFilledSaveHighlighted.png" alt="Project informatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Contactinformatie aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de contactinformatie kader.
        <img src="ProjectDetailContactInformationEditHighlighted.png" alt="Projectdetail met contactinformatie aanpassen aangeduid"/>
    </step>
    <step>
        Vul de nieuwe gegevens in en klik op <shortcut>Opslaan</shortcut>.
        <img src="ProjectEditContactInformationFilledSaveHighlighted.png" alt="Project contactinformatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

### Project foto's aanpassen

<procedure>
    <step>
        Ga naar de <a anchor="project-detail">detailpagina van het project</a>.
    </step>
    <step>
        Klik op het potlood icoontje rechts bovenaan de Project foto's kader.
        <img src="ProjectDetailProjectFotosEditHighlighted.png" alt="Projectdetail met contactinformatie aanpassen aangeduid"/>
    </step>
    <step>
        Kies de gewenste actie, de mogelijke opties zijn: <a anchor="project-foto-s-inspecteren">inspecteren</a>, 
        <a anchor="project-foto-s-uploaden">uploaden</a>, <a anchor="project-foto-s-downloaden">downloaden</a> en <a anchor="project-foto-s-verwijderen">verwijderen</a>.
        <img src="ProjectEditProjectFotos.png" alt="Project contactinformatie aanpassen met opslaan aangeduid"/>
    </step>
</procedure>

#### Project foto's inspecteren

Wanneer u in de inspecteermodus zit, kunt u op een afbeelding klikken om hem te vergroten.
<img src="ProjectEditProjectFotosInspectImageHighlighted.png" alt="Project foto's aanpassen met inspecteermodus met afbeelding aangeduid"/>

Om de vergroting te sluiten kunt u op het kruisje rechts bovenaan de afbeelding klikken of op de <shortcut>escape</shortcut> toets duwen.
<img src="ProjectEditProjectFotosInspectZoomCloseHighlighted.png" alt="Project foto's aanpassen met inspecteermodus vergroot met sluiten aangeduid"/>

#### Project foto's uploaden

<procedure>
    <step>
        Selecteer één of meerdere afbeeldingen.
        <img src="ProjectEditProjectFotosUploadFileSelectHighlighted.png" alt="Project foto's uploaden met afbeelding selecteren aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Upload</shortcut>.
        <img src="ProjectEditProjectFotosUploadUploadHighlighted.png" alt="Project foto's uploaden met uploaden aangeduid"/>
    </step>
</procedure>

#### Project foto's downloaden

<procedure>
    <step>
        Selecteer de afbeeldingen die u wilt downloaden. Dit kan u doen door op de afbeelding te klikken.
        Een geselecteerde afbeelding krijgt een vinkje rechts bovenaan.
        <img src="ProjectEditProjectFotosDownloadSelectHighlighted.png" alt="Project foto's downloaden met afbeelding aangeduid"/>
        Het is ook mogelijk om alle afbeeldingen op een pagina te selecteren door op <shortcut>Pagina Selecteren</shortcut> te klikken.
        <img src="ProjectEditProjectFotosDownloadSelectAllHighlighted.png" alt="Project foto's downloaden pagina selecteren aangeduid"/>
        Wanneer alle afbeeldingen geselecteerd zijn kan u ook alle afbeeldingen deselecteren door op <shortcut>Niets Selecteren</shortcut> te klikken.
        <img src="ProjectEditProjectFotosDownloadDeselectAll.png" alt="Project foto's downloaden met niets selecteren aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Download</shortcut>.
        <img src="ProjectEditProjectFotosDownloadDownloadHighlighted.png" alt="Project foto's downloaden met download aangeduid"/>
    </step>
</procedure>

#### Project foto's verwijderen

<procedure>
    <step>
        Selecteer de afbeeldingen die u wilt verwijderen. Dit kan u doen door op de afbeelding te klikken.
        Een geselecteerde afbeelding krijgt een vinkje rechts bovenaan.
        <img src="ProjectEditProjectFotosDeleteSelectHighlighted.png" alt="Project foto's verwijderen met afbeelding aangeduid"/>
        Het is ook mogelijk om alle afbeeldingen op een pagina te selecteren door op <shortcut>Pagina Selecteren</shortcut> te klikken.
        <img src="ProjectEditProjectFotosDeleteSelectAllHighlighted.png" alt="Project foto's verwijderen pagina selecteren aangeduid"/>
        Wanneer alle afbeeldingen geselecteerd zijn kan u ook alle afbeeldingen deselecteren door op <shortcut>Niets Selecteren</shortcut> te klikken.
        <img src="ProjectEditProjectFotosDeleteDeselectAll.png" alt="Project foto's verwijderen met niets selecteren aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Verwijder</shortcut>.
        <img src="ProjectEditProjectFotosDeleteDeleteHighlighted.png" alt="Project foto's verwijderen met verwijder aangeduid"/>
    </step>
</procedure>
