<script>
  import { _ } from "svelte-i18n";
</script>

<main class="hyphens-manual">
  <!-- Page -->
  <div
    class="p-6 mx-auto page max-w-a4 md:max-w-a4 h-a4 xsm:p-8 sm:p-9 md:p-16"
  >
    <!-- Header -->
    <header class="clearfix mb-8 md:mb-11">
      <div class="float-left flex items-center">
        <div
          class="initials-container mr-5 text-base leading-none text-white
          bg-gray-700 font-medium px-3"
          style="padding-bottom: 0.6875rem; padding-top: 0.6875rem; /*11px*/"
        >
          <div
            class="initial text-center"
            style="padding-bottom: 0.1875rem; /*3px*/"
          >
            E
          </div>
          <div
            class="initial text-center"
            style="padding-bottom: 0.1875rem; /*3px*/"
          >
            C
          </div>
        </div>
        <div class="pb-px">
          <h1 class="text-3xl font-semibold text-gray-750">Eser CANİK</h1>
          <h2 class="text-gray-700">{$_("profession")}</h2>
        </div>
      </div>
      <div class="float-right text-right text-gray-700">
        <ul class="text-right">
          <li class="flex items-center align-right">
            <span class="mr-4 flex-1"
              >Üsküdar, İstanbul, {$_("country")}, 34674</span
            >
            <svg
              class="h-4 w-4 pb-px stroke-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#000000"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <circle cx="12" cy="10" r="3"></circle>
              <path
                d="M12 21.7C17.3 17 20 13 20 10a8 8 0 1 0-16 0c0 3 2.7 6.9 8
                11.7z"
              ></path>
            </svg>
          </li>
          <li class="flex items-center">
            <span class="mr-4 flex-1"><a href="mailto:esercanik@hotmail.com">esercanik@hotmail.com</a></span>
            <svg
              class="h-4 w-4 pb-px stroke-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="none"
              stroke="#4a5568"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            >
              <path
                d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1
                0-2-.9-2-2V6c0-1.1.9-2 2-2z"
              ></path>
              <polyline points="22,6 12,13 2,6"></polyline>
            </svg>
          </li>
          <li class="flex items-center">
            <span class="mr-4 flex-1"><a href="tel:+905364730551">+90 536 473 05 51</a></span>
            <svg
              aria-hidden="true"
              focusable="false"
              class="h-4 w-4 pb-px stroke-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 512 512"
              stroke="#4a5568"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
              ><!-- Font Awesome Free 5.15.1 by @fontawesome - https://fontawesome.com License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License) --><path fill="#4a5568"
                d="M493.4 24.6l-104-24c-11.3-2.6-22.9 3.3-27.5 13.9l-48 112c-4.2 9.8-1.4 21.3 6.9 28l60.6 49.6c-36 76.7-98.9 140.5-177.2 177.2l-49.6-60.6c-6.8-8.3-18.2-11.1-28-6.9l-112 48C3.9 366.5-2 378.1.6 389.4l24 104C27.1 504.2 36.7 512 48 512c256.1 0 464-207.5 464-464 0-11.2-7.7-20.9-18.6-23.4z"
              ></path></svg
            >
          </li>
          <li class="flex items-center">
            <span class="mr-4 flex-1"><a href="https://linkedin.com/in/eser-canik" target="_blank">linkedin.com/in/eser-canik</a></span
            >
            <svg
              class="h-4 w-4 pb-px fill-current"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 24 24"
              fill="#000"
            >
              <path
                d="M22.23 0H1.77C.8 0 0 .77 0 1.72v20.56C0 23.23.8 24 1.77
                24h20.46c.98 0 1.77-.77 1.77-1.72V1.72C24 .77 23.2 0 22.23
                0zM7.27 20.1H3.65V9.24h3.62V20.1zM5.47 7.76h-.03c-1.22
                0-2-.83-2-1.87 0-1.06.8-1.87 2.05-1.87 1.24 0 2 .8 2.02 1.87 0
                1.04-.78 1.87-2.05 1.87zM20.34
                20.1h-3.63v-5.8c0-1.45-.52-2.45-1.83-2.45-1 0-1.6.67-1.87
                1.32-.1.23-.11.55-.11.88v6.05H9.28s.05-9.82
                0-10.84h3.63v1.54a3.6 3.6 0 0 1 3.26-1.8c2.39 0 4.18 1.56 4.18
                4.89v6.21z"
              ></path>
            </svg>
          </li>
        </ul>
      </div>
    </header>

    <hr class="mb-8" />
    <!-- end Name -->

    <!-- Column -->
    <div
      class="md:col-count-2 print:col-count-2 col-gap-md md:h-a4-col
      print:h-a4-col col-fill-auto"
    >
      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.about-me")}
          </h2>

          <section class="mb-4.5 break-inside-avoid">
            <p class="mt-2.1 text-md text-gray-700 leading-normal">
              {$_("about-me")}
            </p>
          </section>
        </div>
      </section>

      <hr class="mt-8" />
      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.education")}
          </h2>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                University of Bahçeşehir
              </h3>
              <p class="leading-normal text-md text-gray-600">
                2014 - 2018 | Software Engineering BSc.
              </p>
            </header>
          </section>
        </div>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              University Of Ordu Ünye Vocational School
            </h3>
            <p class="leading-normal text-md text-gray-600">
              2012 - 2014 | Software Developer Associate Degree
            </p>
          </header>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              Piraziz Çok Programlı Anatolian High School
            </h3>
            <p class="leading-normal text-md text-gray-600">
              2005 - 2009 | Information Technology
            </p>
          </header>
        </section>
      </section>

      <hr class="mt-8" />

      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <!--        <div class="break-inside-avoid">-->
        <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
          {$_("title.experience")}
        </h2>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              YapıKredi Inc. (İstanbul)
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Feb 2022 - Present | Java Developer
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            We are developing needs of department of human resources in
            YapıKredi Inc.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              TÜBİSAD Bilişim Sanayicileri Derneği (İstanbul)
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Dec 2020 - Present | Technical Expert
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            During the work, I am consulting the standardization of TÜBİSAD's
            certificate as a technical expert. Embedded systems, software
            development level 4, level 5, AI system analyst and etc..
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              University of Bahçeşehir Wissen Academy (İstanbul)
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Jun 2018 - Jan 2022 | Software Development Specialist
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            We developed interior software of Bahçeşehir University and gave
            education of software development to students.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              Forex (İstanbul)
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Feb 2018 - Jun 2018 | Internship
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            During the internship, we analyzed, processed, developed algorithms
            for the data of input/output, with Weka program.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              University Of Bahçeşehir (İstanbul)
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Nov 2014 - Jun 2018 | Student Assisting In Dean Office
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            We assisted students for adaptation to school. Management of
            students, student clubs and school events. Were solving problems
            between teachers and students.
          </p>
        </section>
        <!--        </div>-->
      </section>

      <hr class="mt-8" />

      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.references")}
          </h2>
        </div>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              YapıKredi HR Projects
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Since Feb 2022 | Java, ReactJS, Oracle, Spring Boot, Redis,
              RabbitMQ
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            Developing interior needs of YapıKredi human resources department.
            Converting .NET projects to new Java projects.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              Wissen OIS
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Jun 2018 - Jan 2022 | ASP.NET, MSSQL, MongoDB, MVC, Vanilla JS
              Framework
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            An OIS student platform CRM project for Wissen academy. In this
            platform students take online courses, gain certificates and create
            their CVs.
          </p>
        </section>
        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              Wissen Academy Website
            </h3>
            <p class="leading-normal text-md text-gray-650">
              In 2021 | C#, ReactJS, MySQL, MongoDB
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            Official website of Wissen academy. Developed with ASP.NET Core
            architecture.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              Nitelikli Bilişim
            </h3>
            <p class="leading-normal text-md text-gray-650">
              2020 - 2021 | C#, MSSQL, JavaScript, ASP.NET Core
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            An online course platform for University of Bahçeşehir Wissen
            Academy.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              MicroService Project
            </h3>
            <p class="leading-normal text-md text-gray-650">
              2019 - 2020 | Microservices, ASP.NET Core, Docker, RabbitMQ,
              Ocelot API Gateway, MongoDB, Redis, MSSQL
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            An online course platform for University of Bahçeşehir Wissen
            Academy.
          </p>
        </section>

        <section class="mb-4.5 break-inside-avoid">
          <header>
            <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
              CrownApp
            </h3>
            <p class="leading-normal text-md text-gray-650">
              Jun 2018 - 2021 | C#, ASP.NET MVC, MongoDB, MSSQL, Angular
            </p>
          </header>
          <p class="mt-2.1 text-md text-gray-700 leading-normal">
            An online platform for Bahçeşehir schools to plan and manage student
            travelling.
          </p>
        </section>
      </section>
    </div>
  </div>
  <div
    class="p-6 mx-auto page max-w-a4 md:max-w-a4 h-a4 xsm:p-8 sm:p-9 md:p-16"
  >
<!--    <div-->
<!--      class="md:col-count-2 print:col-count-2 col-gap-md md:h-a4-col-->
<!--      print:h-a4-col col-fill-auto"-->
<!--    >-->
      <!--      <hr class="mt-8" />-->

      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.certificates")}
          </h2>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                Machine Learning
              </h3>
              <p class="leading-normal text-md text-gray-600">
                Jul 2020 | Stanford Online (Coursera)
              </p>
              <p class="leading-normal text-md text-gray-600">
                <a
                  href="https://coursera.org/verify/89T87EN7PRRD"
                  target="_blank">coursera.org/verify/89T87EN7PRRD</a
                >
              </p>
            </header>
          </section>
        </div>
      </section>

      <section class="mb-4.5 break-inside-avoid">
        <header>
          <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
            Microsoft Programming C# (70-483)
          </h3>
          <p class="leading-normal text-md text-gray-600">
            Apr 2019 | Microsoft
          </p>
        </header>
      </section>

      <section class="mb-4.5 break-inside-avoid">
        <header>
          <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
            Web and Mobile Expertise (800 hours)
          </h3>
          <p class="leading-normal text-md text-gray-600">
            Dec 2018 | University of Bahçeşehir Wissen Academy
          </p>
        </header>
      </section>

      <section class="mb-4.5 break-inside-avoid">
        <header>
          <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
            Java (SE) (600 hours)
          </h3>
          <p class="leading-normal text-md text-gray-600">
            Jan 2017 | University of Bahçeşehir Wissen Academy
          </p>
        </header>
      </section>

      <hr class="mt-8" />

      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.skills")}
          </h2>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                Java
              </h3>
              <p class="leading-normal text-md text-gray-650">High Level</p>
            </header>
            <div class="my-3.2 last:pb-1.5">
              <ul
                class="flex flex-wrap text-md leading-relaxed -mr-1.6 -mb-1.6"
              >
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  OOP
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Spring
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Hibernate
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  MapStruct
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Play
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Lombok
                </li>
              </ul>
            </div>
          </section>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                C#
              </h3>
              <p class="leading-normal text-md text-gray-650">High Level</p>
            </header>
            <div class="my-3.2 last:pb-1.5">
              <ul
                class="flex flex-wrap text-md leading-relaxed -mr-1.6 -mb-1.6"
              >
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  ASP.NET Core
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  .NET
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Identity Server
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Ajax
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Web Forms
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  ADO.NET
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  MVC
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Entity Framework
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  LINQ
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  AutoMapper
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Azure
                </li>
              </ul>
            </div>
          </section>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                Database
              </h3>
              <p class="leading-normal text-md text-gray-650">High Level</p>
            </header>
            <div class="my-3.2 last:pb-1.5">
              <ul
                class="flex flex-wrap text-md leading-relaxed -mr-1.6 -mb-1.6"
              >
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  MySQL
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  MSSQL
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Oracle
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  MongoDB
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  IBM Db2
                </li>
              </ul>
            </div>
          </section>

          <section class="mb-4.5 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-650 leading-snugish">
                Front-End
              </h3>
              <p class="leading-normal text-md text-gray-650">Middle Level</p>
            </header>
            <div class="my-3.2 last:pb-1.5">
              <ul
                class="flex flex-wrap text-md leading-relaxed -mr-1.6 -mb-1.6"
              >
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  ReactJS
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  JavaScript
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  Angular
                </li>
                <li
                  class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750
                  bg-gray-200"
                >
                  TypeScript
                </li>
              </ul>
            </div>
          </section>
        </div>
      </section>

      <hr class="mt-8" />

      <section class="mt-8 first:mt-0">
        <!-- To keep in the same column -->
        <div class="break-inside-avoid">
          <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-800">
            {$_("title.other")}
          </h2>
        </div>

        <section class="mb-4.5 break-inside-avoid">
          <div class="my-3.2 last:pb-1.5">
            <ul class="flex flex-wrap text-md leading-relaxed -mr-1.6 -mb-1.6">
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                C
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                C++
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Eclipse
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Intelli J Platform
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Matlab
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Dev Express
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                BitBucket
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Jira
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                JFrog
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Bamboo
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Sonar
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Confluence
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Crowd
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                jQuery
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                SignalR
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                RESTful
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                Visual Studio
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                VS Code
              </li>
              <li
                class="px-2.5 mr-1.6 mb-1.6 text-base text-gray-750 bg-gray-200"
              >
                MVC5
              </li>
            </ul>
          </div>
        </section>
      </section>
<!--    </div>-->
    <!-- end Column -->
  </div>
  <!-- end Page -->
</main>
