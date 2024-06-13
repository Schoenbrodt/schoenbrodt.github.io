---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor (Tenure Track)
          company: University of Salzburg
          company_url: 'https://www.plus.ac.at/mathematics/department/staff/schoenbrodt-sarah/?lang=en'
          company_logo: Logo_PLUS
          location: Salzburg, Austria
          date_start: '2023-11-01'
          date_end: ''
        - title: PostDoc and group leader
          company: Karlsruhe Institute of Technology
          company_url: 'https://www.kit.edu/'
          company_logo: Logo_KIT
          location: Karlsruhe, Germany
          date_start: '2022-02-24'
          date_end: '2023-10-31'
          description: |2-
              Responsibilities included:
              * Workshops on mathematical modeling for high-school students
              * Research in the area of mathematics and AI education
              * Leading a team of 3 PhD students and 1 teacher
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Research assistant and doctoral student
          company: Karlsruhe Institute of Technology
          company_url: 'https://www.kit.edu/'
          company_logo: Logo_KIT
          location: Karlsruhe, Germany
          date_start: '2019-05-01'
          date_end: '2022-02-23'
        # #  description: Taught electronic engineering and researched semiconductor physics.
        - title: Exchange semester
          company: Universidad Nacional Autónoma de México
          company_url: 'https://www.unam.mx/'
          # company_logo: org-x
          location: Mexico City, Mexico
          date_start: '2016-08-01'
          date_end: '2017-01-30'
        # #  description: Taught electronic engineering and researched semiconductor physics.
        - title: Research assistant
          company_logo: RWTH_Logo_3
          company_url: 'https://www.rwth-aachen.de/'
         # company_logo: org-x
          location: Aachen, Germany
          date_start: '2018-05-01'
          date_end: '2019-04-30'
          # description: Taught electronic engineering and researched semiconductor physics.
        - title: Teacher
          company: Einhard Gymnasium Aachen
          company_url: https://www.einhard-gymnasium.de/
          location: Aachen, Germany
          date_start: '2017-02-01'
          date_end: '2017-09-30'
        - title: Internship at Colegio Humboldt
          company: Colegio Humboldt
          company_url: https://www.humboldt.ed.cr/?lang=de
          location: San José, Costa Rica
          date_start: '2014-09-01'
          date_end: '2014-10-15'
        - title: Internship at the 4. Aachener Gesamtschule
          company: Vierte Aachener Gesamtschule
          company_url: https://www.aachener-gesamt.schule/
          location: Aachen, Germany
          date_start: '2014-04-01'
          date_end: '2014-07-15'
        - title: Internship at the German School Montevideo
          company: Deutsche Schule Montevideo
          company_url: https://www.dsm.edu.uy/de/
          location: Montevideo, Uruguay
          date_start: '2014-03-01'
          date_end: '2014-04-01'
    design:
      columns: '2'
  - block: markdown
    id: awards
    content:
      title: Awards and Scholarships
      text:   
            <ul>
            <li><b>Idea contest within the framework of the Civic Innovation Platform of the Federal Ministry of Labour and Social Affairs,</b> Award for the  idea "AI Teaching Platform" in cooperation with  KI macht Schule  and KIT, 2023</li>
            <li><b>Springer BestMasters,</b> Award for an outstanding master's thesis, 2018</li>
            <li><b>Brigitte Gilles Prize of RWTH Aachen University,</b> Prize for promoting female students in the STEM field within the CAMMP student laboratory, 2018</li>
            <li><b>Schöneborn Prize of RWTH Aachen University,</b> Prize for the best completion in Bachelor of Education in Chemistry, 2016</li>
            <li><b>Dean’s List of RWTH Aachen University,</b> Award for outstanding academic achievements (top 5% of each year's cohort), 2013–2018</li>
            <li><b>Westfälischer Arbeitgeberverband Scholarship,</b> Support for gifted students in STEM subjects, 2013–2017</li>
            <li><b>Foundation of German Business Scholarship,</b> Support for gifted students based on exceptional academic performance and extracurricular engagement, 2012–2018</li>
            <li><b>High-school awards from DMV and GDCh</b> for outstanding achievements in Mathematics and Chemistry, 2012</li>
            </ul>
    design:
      columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: markdown # https://wowchemy.com/blocks/markdown/
    id: teaching
    content:
        title: Teaching
        subtitle: Courses and supervised students
        text: <h2>University Teaching</h2>
              <h3>Summer Semesters 2024</h3>
              <ul>
              <li>Lecture <i>Introduction to didactics for mathematics I</i>, Universität Salzburg</li>
              <li>Lecture <i>Introduction to didactics for mathematics II</i>, Universität Salzburg</li>
              <li><i>Master's thesis (M.Ed.) Seminar for Mathematics</i>, University Salzburg</li>
              </ul>
              <h3>Winter Semester 2023/24</h3>
              <ul>
              <li><i>Master's thesis (M.Ed.) Seminar for Mathematics</i>, University Salzburg</li>
              <li><i>Didactics seminar</i>, University Salzburg</li>
              </ul>
              <h3>Summer Semester 2023</h3>
              <ul>
              <li>Seminar <i>Fundamentals of Artificial Intelligence and its Application in all School Subjects</i>, KIT</li>
              <li>Seminar <i>Data Analysis and Big Data</i>, Hochschule Biberach</li>
              </ul>
              <h3>Winter Semester 2022/23</h3>
              <ul>
              <li>Seminar <i>Fundamentals of Artificial Intelligence and its Application in all School Subjects</i>, University of Konstanz</li>
              <li>Seminar <i>Digital-Based Learning Contexts in Mathematics Education</i>, KIT</li>
              </ul>
              <h3>Winter Semester 2021/22</h3>
              <ul>
              <li>Seminar <i>Fundamentals of Artificial Intelligence and its Application in all School Subjects</i>, University of Konstanz</li>
              </ul>
              <h3>Winter Semester 2020/21</h3>
              <ul>
              <li>Seminar <i>Individual Subject Didactics Project</i>, KIT</li>
              </ul>
              <h3>Summer Semester 2020</h3>
              <ul>
              <li>Seminar <i>Individual Subject Didactics Project</i>, KIT</li>
              </ul>
              <h3>Winter Semester 2019/20</h3>
              <ul>
              <li>Seminar <i>Individual Subject Didactics Project</i>, KIT</li>
              </ul>
              <h3>2014-2019:</h3>
              <ul>
              <li><b>Summer Semesters 2018 and 2019:</b> <i>Excursion Week on Mathematical Modeling (CAMMP week Pro)</i>, Seminar for B.Sc./M.Sc. Mathematics, Simulation Science, and CES Students, RWTH Aachen</li>
              <li><b>Winter Semester 2014/15:</b> Tutor for Higher Mathematics I, RWTH Aachen</li>
              </ul>
              <h2>Supervised Theses</h2>
              <ul>
              <li>Diehle, S. (2023). Optimization of Wind Turbines as a Topic for Interdisciplinary Computer-Aided Modeling Projects, Bachelor's Thesis, KIT.</li>
              <li>Maier, R. (2023). Recommender Systems and Artificial Intelligence – Development and Evaluation of an Interdisciplinary Learning Module on the Topic of AI in the Media Industry, Master's Thesis.</li>
              <li>Hoeffer, K. (2022). Activity Recognition on Smartphones – Development of Teaching Material for Computer-Aided Mathematical Modeling Projects, Master's Thesis, KIT.</li>
              <li>Rantzau, L. (2021). Recommendation Systems Based on Neighborhood Methods – Mathematical-Subject Discussion and Development of Digital Learning Material for the Netflix Challenge for Secondary Level II Students, Bachelor's Thesis, KIT.</li>
              <li>Hoeffer, K. (2020). Development of Teaching Material on Solar Energy within an Interdisciplinary Mathematical Modeling Project, Bachelor's Thesis, KIT.</li>
              <li>Schmidt, L. (2019). Machine Learning - Automatic Image Recognition with Mathematics?! A Teaching-Learning Module in the Context of a Mathematical Modeling Day for Upper Secondary Students, Master's Thesis, RWTH Aachen.</li>
              </ul>
    design:
      columns: '2'

  - block: markdown # https://wowchemy.com/blocks/markdown/
    id: outreach
    content:
      title: Outreach
      subtitle: Teacher Trainings and School Projects
      text: |
              <h2>Teacher Training and Professional Development</h2>
              <h3>2024</h3>
              <ul>
               <li><b>AI Education in  Mathematics Education,</b> Workshop on the 35th Swiss Day of Mathematics and Teaching 2024, Zürich, Sitzwerland, September 2024</li>
               <li><b>AI Education in  Mathematics Education,</b> Talk and Workshop on the Austrian Day of Mathematics Education 2024, Linz, Austria, September 2024</li>
               <li><b>Bildung with and on AI  in the classroom,</b> Two Workshops on the Day of Digital Teaching, Salzburg, Austria, June 2024</li>
               <li><b>Opening the Blackbox - - A commonly understandable insight into the fundamentals of AI for all subjects,</b> Workshop for teachers at BHAK /BHAS 1, Salzburg, May 2024</li>
               </ul>
              <h3>2023</h3>
              <ul>
              <li><b>Exploring Modern Applications of Mathematics through Computer-Aided Materials,</b> Workshop at the Teachers Day of the ISTRON Conference, Vienna, September 2023</li>
              <li><b>Opening the Blackbox - A commonly understandable insight into the fundamentals of AI for all subjects,</b> invited presentation as part of the teacher training series "Opportunities & Risks of the Digital Transformation" by ZSL and ZLB, Karlsruhe, June 2023</li>
              <li><b>Mathematical Modeling and Data Science,</b> (multi-day) Training for participating teachers at CAMMP week, Belgium, June 2023</li>
              <li><b>Exploring modern applications computer-aided,</b> Workshop at the Digital Mathematical Tools Conference, Karlsruhe, March 2023</li>
              </ul>
              <h3>2022</h3>
              <ul>
              <li><b>Fundamentals of AI and Its Application in All Subjects,</b> Justus Liebig University Giessen, invited workshop (6 hours) for (prospective) teachers, online, November 2022</li>
              <li><b>Digital learning materials for AI and Data Science in mathematics education,</b> Workshop at the Teachers Day of the ISTRON Conference, Karlsruhe, November 2022</li>
              <li><b>Opportunities for Machine Learning in Mathematics Education,</b> Teacher Training by invitation from the Department of Education and Sports of the City of Munich, Munich, September 2022</li>
              </ul>
              <h3>2018 – 2021</h3>
              <ul>
              <li>Invited Workshop for prospective teachers in the seminar on "Applied Mathematics Education", TU Darmstadt, online, June 2021</li>
              <li><b>Materials for Computer-Aided Solar Energy Research with high-school students,</b> Teacher Training as part of the STEM Congress, online, November 2020</li>
              <li>Workshop for Teacher Education Students in the Seminar on "Digital Tools for Mathematics Education", KIT, online, July 2020</li>
              <li>Invited Workshop for prospective teachers in the Seminar on "Application and Modeling", RWTH Aachen, online, June 2020</li>
              <li>Invited Workshop for prospective teachers  in the Seminar on "Application and Modeling", RWTH Aachen, Aachen, November 2019</li>
              <li><b>Solar Energy research with high-school students in the context of a computer-aided project day,</b> presentation at the Teachers Day of the ISTRON Conference, Berlin, September 2019</li>
              <li><b>Opportunities for Machine Learning in Mathematics Education,</b> Presentation at the Teachers Day of the ISTRON Conference, Würzburg, October 2018</li>
              </ul>
              <h2>School Projects</h2>
               <ul>     
               <li><b>09–12/2022:</b> Design and implementation of the project course <a href="https://www.scc.kit.edu/forschung/16168.php">Girls Do STEM - solving real problems with math and AI</a>, Karlsruhe</li>
              <li><b>Summer Semester 2021:</b> Design and Implementation of the <a href="https://www.scc.kit.edu/forschung/14727.php">Introductory Course Mathematics for high-school students</a> </li> at KIT</li>
              <li><b>10/2019:</b> Design and implementation of mathematical modeling days at the Autonomous University of Baja California, Tijuana, Mexico</li>
              <li><b>Since 2019:</b> Organization and supervision of various mathematical modeling weeks for high-school students (<a href="https://www.cammp.online/21.php">CAMMP week</a>)</li>
              <li><b>Since 2015:</b> Organization, design, and supervision of numerous mathematical modeling days for high-school students (<a href="https://www.cammp.online/116.php">CAMMP day</a>, RWTH Aachen und KIT)</li> 
              <li><b>2017:</b> Substitute teacher at Einhard Gymnasium Aachen</li>
              </ul>
              <div style="display: flex; justify-content: center; gap: 100px; margin-bottom: 20px;">
              <img src="/images/cammp.png" alt="CAMMP logo" style="max-width: 45%; height: auto;">
              <img src="/images/kims2.svg" alt="KImS Logo" style="max-width: 45%; height: auto;">
              </div>
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
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
  # - block: contact
  #   id: contact
  #   content:
  #     title: Contact
  #     subtitle:
  #     text: |-
  #       Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
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
   #   contact_links:
    #    - icon: twitter
    #      icon_pack: fab
    #      name: DM Me
    #      link: 'https://twitter.com/Twitter'
    #    - icon: skype
    #      icon_pack: fab
    #      name: Skype Me
    #      link: 'skype:echo123?call'
    #    - icon: video
    #      icon_pack: fas
    #      name: Zoom Me
    #      link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
    #  autolink: true
      # Email form provider
    #  form:
    #    provider: netlify
    #    formspree:
    #      id:
    #    netlify:
          # Enable CAPTCHA challenge to reduce spam?
    #      captcha: false
    design:
      columns: '2'
---
