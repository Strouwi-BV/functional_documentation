# Check in And Out At Work

<primary-label ref="location_registration_primary"/>

<p>
Check In and Out at Work (CiAO) is de onlinedienst van de Sociale Zekerheid voor 
het registreren van aanwezigheden op het werk.
Het gaat om de registratie van iedereen die werk uitvoert in een van de doelsectoren.<br/>
U kan meer informatie vinden op de website van de 
<a href="https://www.socialsecurity.be/site_nl/employer/applics/check-in-and-out-at-work/index.htm">RSZ</a>.
</p>

## Buildbase CiAO registratie

<p>
Buildbase stuurt de <b>in</b> en <b>out</b> registraties automatisch door naar de RSZ bij het in- en uitklokken
door de werknemer.
</p>

### Voorwaarden
Voor het automatisch registreren, dient er aan volgende voorwaarden voldaan te zijn:

- BTW - nummer van de organisatie moet correct ingevuld zijn
  <img src="CiaoCorrectVatNumber.png" alt="Klantdetail met op inactief zetten aangeduid"/>
- Rijksregisternummer van de werknemer moet correct ingevuld zijn
  <img src="CiaoCorrectNationalRegisterNumber.png" alt="Klantdetail met op actief zetten aangeduid"/>
- het project waar de registratie op van toepassing is, moet een geldig <b>Aangifte van werken</b> nummer bevatten.
  <img src="CiaoCorrectContractualRelationshipReference.png" alt="Klantdetail met op actief zetten aangeduid"/>
  <warning>Als de aangifte van werken nummer ontbreekt, wordt er geen CiAO registratie uitgevoerd!</warning>

### Registratie status raadplegen in Buildbase

#### Werknemer

Na het in- en uitklokken door de werknemer, kan deze de status van de registaties raadplegen.
<procedure>
    <step>
        Ga direct naar <a href="%url_buildbase%/calendar"/>.<br/>
        Of klik op <shortcut>kalender</shortcut> in het hoofdmenu.
        <img src="MainMenuCalendarHighlighted.png"  alt="Hoofdmenu met kalender aangeduid"/>
    </step>
    <step>
        Duid de gewenste dag aan, waarvan u de registraties wil raadplegen.
        <img src="CalendarDesiredDayToConsultHighlighted.png"  alt="Kalender met gewenste dag aangeduid"/>
        U wordt doorverwezen naar de gedetaileerde pagina van de zojuist geselecteerde dag.
    </step>
    <step>
        Het groene icoon onder CiAO geeft aan dat de registraties goed verlopen zijn. Voor meer informatie kan u over 
        het icoon bewegen:        
        <img src="CiaoHoverIconSuccessCloseup.png"  alt="Registratie met extra informatie"/>
    </step>
</procedure>

#### Beheerder
Een beheerder kan de registraties van de werknemers nakijken.
<procedure>
    <step>
        Ga naar de detailpagina van de werknemer.
    </step>
    <step>
        Klik op <shortcut>Acties</shortcut>.
        <img src="EmployeeDetailHeaderActionsHighlighted.png" alt="Werknemerdetail met acties aangeduid"/>
    </step>
    <step>
        Klik op <shortcut>Registreer uren</shortcut>.
        <img src="EmployeeDetailActionsRegisterHoursHighlighted.png" alt="Werknemerdetail met op inactief zetten aangeduid"/>
        U ziet nu de kalenderpagina van de werknemer, waar u de registaties van de gewenste dag kan raadplegen.
        <img src="EmployeeDetailActionsRegisterHoursCalendar.png" alt="Kalender van werknemer"/>
    </step>
</procedure>

## RSZ CiAO portaal

Zowel de werknemer als de onderneming/onderaanneming kan de registraties raadplegen op het portaal van de RSZ.

### Portaal werknemer

<a href="https://checkinout.socialsecurity.be">https://checkinout.socialsecurity.be</a>
<img src="RSZ_portaal_werknemer.png" alt="RSZ portaal werknemer"/>

### Portaal werkgever

<a href="https://checkinout-management.socialsecurity.be">https://checkinout-management.socialsecurity.be</a>

