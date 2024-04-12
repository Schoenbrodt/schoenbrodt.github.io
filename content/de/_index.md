---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biographie
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Erfahrung
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: TT-Assistenzprofessorin
          company: Paris Lodron Universität Salzburg
          company_url: 'https://www.plus.ac.at/mathematik/fachbereich/team/schoenbrodt-sarah/'
          company_logo: Logo_PLUS
          location: Salzburg, Österreich
          date_start: '2023-11-01'
          date_end: ''
        - title: PostDoc und Nachwuchsgruppenleiterin
          company: Karlsruher Institut für Technologie
          company_url: 'https://www.kit.edu/'
          company_logo: Logo_KIT
          location: Karlsruhe, Deutschland
          date_start: '2022-02-24'
          date_end: '2023-10-31'
          description: |2-
              Tätigkeiten beinhalten:
              * Workshops zur mathematischen Modellierung für Schüler:innen
              * Forschung im Bereich Mathematikdidaktik und KI-Bildung
              * Leitung eines Teams aus Doktoranden und Lehrkräften
          # description: Taught electronic engineering and researched semiconductor physics. 
          #* Forschung im Bereich Mathematikdidaktik und KI-Bildung
        - title: Wissenschaftliche Mitarbeiterin und Doktorandin
          company: Karlsruher Institut für Technologie
          company_url: 'https://www.kit.edu/'
          company_logo: Logo_KIT
          location: Karlsruhe, Deutschland
          date_start: '2019-05-01'
          date_end: '2022-02-23'
        # #  description: Taught electronic engineering and researched semiconductor physics.
        - title: Wissenschaftliche Mitarbeiterin
          company: RWTH Aachen, Lehrstuhl II für Mathematik 
          company_url: 'https://www.rwth-aachen.de/'
          company_logo: RWTH_Logo_3
          location: Aachen, Deutschland
          date_start: '2018-05-01'
          date_end: '2019-04-30'
        - title: Vertretungslehrkraft
          company: Einhard Gymnasium Aachen
          company_url: https://www.einhard-gymnasium.de/
          location: Aachen, Deutschland
          date_start: '2017-02-01'
          date_end: '2017-09-30'
        - title: Auslandssemester
          company: Universidad Nacional Autónoma de México
          company_url: 'https://www.unam.mx/'
          # company_logo: Escudo-UNAM-escalable
          location: Mexico City
          date_start: '2016-08-01'
          date_end: '2017-01-30'
        - title: Praktikum am Colegio Humboldt
          company: Colegio Humboldt 
          company_url: https://www.humboldt.ed.cr/?lang=de
          location: San José, Costa Rica
          date_start: '2014-09-01'
          date_end: '2014-10-15'
        - title: Praktikum an der 4. Aachener Gesamtschule
          company: Vierte Aachener Gesamtschule
          company_url: https://www.aachener-gesamt.schule/
          location: Aachen, Germany
          date_start: '2014-04-01'
          date_end: '2014-07-15'
        - title: Praktikum an der Deutschen Schule Montevideo
          company: Deutsche Schule Montevideo
          company_url: https://www.dsm.edu.uy/de/
          location: Montevideo, Uruguay
          date_start: '2014-03-01'
          date_end: '2014-04-01'
         # description: |2-
          #    Responsibilities include:
              #* Analysing
              #* Modelling
              #* Deploying
    design:
      columns: '2'
  - block: markdown
    id: awards
    content:
      title: Preise, Aus- zeichnungen und Stipendien
      text:   <ul> 
              <li><b>Ideenwettbewerb im Rahmen der Civic Innovation Plattform des Bundesministeriums für Arbeit und Soziales,</b> Auszeichnung der Idee „KI-Lehrplattform“ in Kooperation der Initiative KI macht Schule und des KIT, 2023</li>
              <li><b>Springer BestMasters,</b> Auszeichnung für eine herausragende Masterarbeit, 2018</li>
              <li><b>Brigitte Gilles Preis der RWTH Aachen,</b>  Preis für die Förderung von Schülerinnen im MINT-Bereich im Rahmen des Schülerlabors CAMMP, 2018</li>
              <li><b>Schöneborn Preis der RWTH Aachen,</b> Preis für den besten Abschluss im Bachelor Lehramt Chemie, 2016</li>
              <li><b>Dean’s List der RWTH Aachen,</b> Auszeichnung für herausragende Studienleistungen (top 5% des jeweiligen Jahrgangs), 2013–2018</li>
              <li><b>Stipendium des Westfälischen Arbeitgeberverbands,</b> Förderung begabter Studierender in MINT-Fächern, 2013–2017 </li>
              <li><b>Stipendium der Stiftung der deutschen Wirtschaft,</b> Förderung begabter Studierender basierend auf herausragenden Studienleistungen und extracurricularem Engagement, 2012–2018</li>
              <li><b>Abiturpreise von DMV und GDCh</b> für herausragende Abiturleistungen in Mathematik und Chemie, 2012</li> 
              </ul>
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Publikationen
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Vorträge
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: markdown # https://wowchemy.com/blocks/markdown/
    id: teaching
    content:
        title: Lehre
        subtitle: Lehrveranstaltungen und betreute Abschlussarbeiten
        text: <h2>Universitäre Lehre</h2>
              <h3>SoSe 24</h3>
              <ul>
              <li>Vorlesung <i>Einführung in die Mathematikdidaktik I</i>, Universität Salzburg</li>
              <li>Vorlesung <i>Einführung in die Mathematikdidaktik II</i>, Universität Salzburg</li>
              <li><i>Seminar zur Masterarbeit für Lehramt Mathematik</i>, Universität Salzburg</li>
              </ul>
              <h3>WiSe 23/24</h3>
              <ul>
              <li><i>Seminar zur Masterarbeit für Lehramt Mathematik</i>, Universität Salzburg</li>
              <li><i>Fachdidaktisches Seminar</i>, Universität Salzburg</li>
              </ul>
              <h3>SoSe 23</h3>
              <ul> 
              <li>Blockseminar <i>Grundlagen Künstlicher Intelligenz und ihre Anwendung in allen Schulfächern</i>, KIT</li>
              <li>Blockseminar <i>Datenanalyse und Big Data</i>, Hochschule Biberach </li>
              </ul>
               <h3>WiSe 22/23</h3>
               <ul> <li>Blockseminar <i>Grundlagen Künstlicher Intelligenz und ihre Anwendung in allen Schulfächern</i>, Universität Konstanz</li>
                <li>Seminar <i>Digitalbasierte Lernkontexte des Mathematikunterrichts</i>, KIT </li>
               </ul>
               <h3>WiSe 21/22</h3>
                <ul>
                <li>Blockseminar <i>Grundlagen Künstlicher Intelligenz und ihre Anwendung in allen Schulfächern</i>, Universität Konstanz</li>
               </ul>
               <h3>WiSe 20/21</h3>
                <ul>
                <li>Seminar <i>Individuelles Fachdidaktikprojekt</i>, KIT</li>
               </ul>
                <h3>SoSe 20</h3>
                <ul>
                <li>Seminar <i>Individuelles Fachdidaktikprojekt</i>, KIT</li>
               </ul>
                  <h3>WiSe 19/20</h3>
                <ul>
                <li>Seminar <i>Individuelles Fachdidaktikprojekt</i>, KIT</li>
               </ul>
               
               <h3>2014 – 2019</h3>
                <ul>
                <li><b>SoSe 2018 und SoSe 2019</b> <i>Exkursionswoche zur mathematischen Modellierung (CAMMP week Pro)</i>, Seminar für Studierende im B.Sc./M.Sc. Mathematik, Simulation Science und CES, RWTH Aachen</li>
                <li><b>WiSe 14/15</b> Tutorin für Höhere Mathematik I, RWTH Aachen</li>               
              </ul>
    
              <h2>Betreute Abschlussarbeiten</h2>
              <ul>
              <li>Diehle, S. (2023). Optimierung von Windkraftwerken als Thema interdisziplinärer, computergestützter Modellierungsprojekte, Bachelorarbeit, KIT.  </li>
               <li>Maier, R. (2023). Empfehlungssysteme und KI – Entwicklung und Erprobung eines interdisziplinären Lernmoduls zum Thema KI in der Medienbranche, Masterarbeit, KIT.</li>
               <li>Hoeffer, K. (2022). Aktivitätserkennung auf dem Smartphone – Entwicklung von Unterrichtsmaterial für computergestützte mathematische Modellierungsprojekte, Masterarbeit, KIT. </li>
               <li>Rantzau, L. (2021). Empfehlungssysteme basierend auf Nachbarschaftsmethoden – mathematisch-fachliche Diskussion und Entwicklung digitalen Lernmaterials zur Netflix Challenge für Schüler*innen der Sekundarstufe II, Bachelorarbeit, KIT. </li>
               <li>Hoeffer, K. (2020).  Entwicklung von Unterrichtsmaterial zum Thema Solarenergie im Rahmen eines interdisziplinären mathematischen Modellierungsprojektes, Bachelorarbeit, KIT.</li>
               <li>Schmidt, L. (2019). Machine Learning - automatische Bilderkennung mit Mathematik?! Ein Lehr-Lern-Modul im Rahmen eines mathematischen Modellierungstages für Schülerinnen und Schüler der Sekundarstufe II, Masterarbeit, RWTH Aachen.</li>
               </ul>
    design:
      columns: '2'
  - block: markdown # https://wowchemy.com/blocks/markdown/
    id: outreach
    content:
        title: Outreach
        subtitle: Lehrkräftefortbildungen und Schulprojekte
        text: <h2>Aus- und Fortbildung von Lehrkräften</h2>
              <h3>2024</h3> 
              <ul>
               <li><b>KI-Bildung im Mathematikunterricht,</b> Workshop auf dem 34. Schweizerischen Tag über Mathematik und Unterricht 2024, Zürich, September 2024</li>
               <li><b>Bildung mit und über KI im Unterricht,</b> Workshop auf dem Tag des Digitalen Lernens, Salzburg, Juni 2024</li>
               <li><b>Opening the Blackbox - Ein allgemeinverständlicher Einblick in die Grundlagen der KI für alle Schulfächer,</b> Workshop für die BHAK /BHAS 1, Salzburg, Mai 2024</li>
               </ul>
              <h3>2023</h3> 
               <ul>
               <li><b>Moderne Anwendungen der Mathematik computergestützt erarbeiten,</b> Workshop auf dem Lehrkräftetag der ISTRON-Herbsttagung, Wien, September 2023</li>
               <li><b>Opening the Blackbox - Ein allgemeinverständlicher Einblick in die Grundlagen der KI für alle Schulfächer,</b> eingeladener Vortrag im Rahmen der Fortbilungsreihe Chancen & Risiken der digitalen Transformation von ZSL und ZLB, Karlsruhe, Juni 2023</li>
               <li><b>Mathematische Modellierung und Data Science,</b> (mehrtägige) Fortbildung für teilnehmende Lehrkräfte der CAMMP week, Belgien, Juni 2023 </li>
               <li><b>Moderne Anwendung computergestützt erarbeiten,</b> Workshop auf der Digitale Mathematische Werkzeuge-Tagung, Karlsruhe, März 2023</li>
               </ul>
               <h3>2022</h3> 
               <ul>
               <li><b>Grundlagen der KI und ihre Anwendung in allen Schulfächern,</b> Justus-Liebig-Universität Gießen, eingeladener Workshop (6-stündig) für (angehende) Lehrkräfte, online, November 2022</li>
               <li><b>Digitales Lernmaterial zu KI und Data Science für den Mathematikunterricht,</b> Workshop auf dem Lehrkräftetag der ISTRON-Herbsttagung, Karlsruhe, November 2022</li>
               <li><b>Chancen für Machine Learning im Mathematikunterricht,</b>  Lehrerfortbildung auf Einladung des Referats für Bildung und Sport der Landeshauptstadt München, München, September 2022</li>
               </ul>
               <h3>2018 – 2021</h3> 
               <ul>
               <li>Eingeladener Workshop für Lehramtsstudierende im Seminar Anwendungsorientierter Mathematikunterricht, TU Darmstadt, online, Juni 2021</li>
               <li><b>Material für computergestützte Solarenergieforschung mit Schüler/innen,</b> Lehrerfortbildung im Rahmen des MINT-Kongress, online, November 2020 </li>
               <li>Workshop für Lehramtsstudierende im Seminar Digitale Werkzeuge für den Mathematikunterricht, KIT, online, Juli 2020</li>
               <li>Eingeladener Workshop für Lehramtsstudierende im Seminar Anwendung und Modellierung, RWTH Aachen, online, Juni 2020</li>
                <li>Eingeladener Workshop für Lehramtsstudierende im Seminar Anwendung und Modellierung, RWTH Aachen, Aachen, November 2019</li>
               <li><b>Solarenergieforschung mit Schüler/innen im Rahmen eines computergestützten Projekttages (Sek I/II),</b> Vortrag auf dem Lehrkräftetage der ISTRON-Herbsttagung, Berlin, September 2019</li>
               <li><b>Chancen für Machine Learning im Mathematikunterricht (Sek. II),</b> Vortrag auf dem Lehrkräftetage der ISTRON-Herbsttagung, Würzburg, Oktober 2018  </li>
               </ul>
               <h2>Schulprojekte (Auswahl)</h2>
               <ul>
               <li><b>09-12/2022:</b> Gestaltung und Durchführung des Projektkurses <a href="https://www.scc.kit.edu/forschung/16168.php">Mädels machen MI(NT) - Mit Mathe und KI reale Probleme lösen</a>, Karlsruhe</li>
               <li><b>SoSe 21:</b> Gestaltung und Durchführung des <a href="https://www.scc.kit.edu/forschung/14727.php">Schnupperkurses Mathematik des KIT</a> </li>
              <li><b>09-12/2022:</b> Gestaltung und Durchführung von Workshops zur KI im Rahmen von<a href="https://ki-macht-schule.de/"> KI macht Schule</a>, Deutschland und Österreich</li>
               <li><b>10/2019:</b> Gestaltung und Durchführung von mathematischen Modellierungstagen an der Autonomous University of Baja California, Tijuana, Mexiko</li>
               <li><b>Seit 2019:</b> Organisation und Betreuung von diversen mathematischen Modellierungswochen für Schüler:innen (<a href="https://www.cammp.online/21.php">CAMMP week</a>)</li> 
               <li><b>Seit 2015:</b> Organisation, Gestaltung und Betreuung zahlreicher mathematischer Modellierungstage für Schüler:innen (<a href="https://www.cammp.online/116.php">CAMMP day</a>, Aachen, Karlsruhe und Salzburg)</li>  
               <li><b>2017:</b> Vertretungslehrkraft am Einhard-Gymnasium Aachen</li>
               </ul>
    design:
      columns: '2'
#   - block: XYZ
 #    content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  #- block: contact
  #  id: contact
    # content:
    #   title: Kontakt
    #   subtitle:
    #   text: |-
    #     Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
    #   # Contact (add or remove contact options as necessary)
    #   email: test@example.org
    #   phone: 888 888 88 88
    #   appointment_url: 'https://calendly.com'
    #   address:
    #     street: 450 Serra Mall
    #     city: Stanford
    #     region: CA
    #     postcode: '94305'
    #     country: United States
    #     country_code: US
    #   directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    #   office_hours:
    #     - 'Monday 10:00 to 13:00'
    #     - 'Wednesday 09:00 to 10:00'
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      #  - icon: skype
      #    icon_pack: fab
      #    name: Skype Me
      #   link: 'skype:echo123?call'
      #  - icon: video
      #    icon_pack: fas
      #    name: Zoom Me
      #    link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      #autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
       #   # Enable CAPTCHA challenge to reduce spam?
       #   captcha: false
    design:
      columns: '2'
---
