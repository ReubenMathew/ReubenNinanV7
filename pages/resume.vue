<template>
  <div class="font-firago hyphens-manual">
    <div class="p-6 mx-auto page max-w-2xl print:max-w-letter md:max-w-letter md:h-letter xsm:p-8 sm:p-9 md:p-16 bg-white">
      
      <!-- Based on template from https://github.com/WebPraktikos/universal-resume -->

      <!-- Name -->
      <header class="flex items-center mb-8 md:mb-11">
        <router-link to="/" class="initials-container mr-5 text-base leading-none text-white bg-gray-700 font-medium print:bg-black px-3 py-3">
          <div class="initial text-center pb-0.8">R</div>
          <div class="text-center initial">N</div>
        </router-link>
        <div class="flex-col">
        <h1 class="text-2xl font-semibold text-gray-750">
          Reuben Ninan
        </h1>
        <nuxt-link class="text-lg font-semibold text-gray-600" to="/">Go back</nuxt-link>
        </div>
      </header>
<!-- Column -->
      <div class="md:col-count-2 print:col-count-2 col-gap-md md:h-letter-col print:h-letter-col col-fill-auto">

        <!-- Use mt-3 class when the element isn’t the first one in the column -->
        <section>

          <!-- To keep in the same column -->
          <div class="break-inside-avoid">

            <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-550 print:font-normal">
              ABOUT ME
            </h2>

            <section class="mb-4 break-inside-avoid">
              <header>
              </header>
              <p class="mt-2 text-md text-gray-700 leading-normal">
                Motivated and dedicated Software Engineering student looking to leverage my technical acumen
                and passion for engineering with my leadership and coaching skills.
              </p>
            </section>

          </div>



        </section>

        <section class="mt-8">

          <!-- To keep in the same column -->
          <div class="break-inside-avoid">
            <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-550 print:font-normal">
              EXPERIENCE
            </h2>
          </div>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                Royal Bank of Canada (RBC)
              </h3>
              <p class="leading-normal text-md text-gray-650">
                Apr 2019 – Aug 2019 | Data Scientist (Intern)
              </p>
            </header>
            
            <ul class="">

              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                Automated data loading and cleaning processes
              </li>

              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                    Extracted <b>500gb</b> of unstructured data from legacy files,<br>
                    The data was cleansed and enriched with existing data sources for the purpose of
                    validation and governance
              </li>
              
              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                    Presented a dashboard displaying visual, statistical and 
                    geographic insights on the newly extracted dataset to Senior Management
              </li>

              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                    Worked under Agile/SCRUM Methodologies and utilized tools such as JIRA, Enterprise GitHub and Confluence
              </li>

              <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
                
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Python
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Tableau
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  SQL
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Bash
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  R
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Java
                </li>                
              </ul>
            </ul>
          </section>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="https://www.stem1.ca/" class="group">
                  STEM1
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
              </h3>
              <p class="leading-normal text-md text-gray-650">
                Jun 2018 – Aug 2018 | Computer Science Instructor
              </p>
            </header>
            <ul class="">
              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                Taught computer programs, algorithms and computer design to students (K-12)
              </li>
              <li class="mt-2 text-md text-gray-700 leading-normal">
                <span class="absolute -ml-3 sm:-ml-3.2 select-none transform -translate-y-px">›</span>
                Created and implemented a beginner’s curriculum focused on robotics
              </li>
            </ul>
          </section>

        </section>

        <section class="mt-8">

          <!-- To keep in the same column -->
          <div class="break-inside-avoid">

            <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-550 print:font-normal">
              EDUCATION
            </h2>

            <section class="mb-4 break-inside-avoid">
              <header>
                <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                  York University - Software Engineering
                </h3>
                <p class="leading-normal text-md text-gray-650">
                  2018 – Current | Bachelor of Engineering
                </p>
              </header>
            </section>

          </div>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                Chinguacousy Secondary School
              </h3>
              <p class="leading-normal text-md text-gray-650">
                2014 – 2018 | Sci-Tech Regional Program
              </p>
            </header>
          </section>


<div class="break-inside-avoid">

            <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-550 print:font-normal">
              LEADERSHIP
            </h2>

            <section class="mb-4 break-inside-avoid">
              <header>
                <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                  Codespot - Computer Science Instructor
                </h3>
                <p class="leading-normal text-md text-gray-650">
                  2017 – 2018 | Chinguacousy Secondary School
                </p>
              </header>
            </section>

          </div>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="http://www.wolfhacks.ca/" class="group">
                  WolfHacks Hackathon - Financial Head
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
                
              </h3>
              <p class="leading-normal text-md text-gray-650">
                2017 – 2018 | Peel District School Board
              </p>
            </header>
          </section>

        </section>


        <section class="mt-8">

          <!-- To keep in the same column -->
          <div class="break-inside-avoid">

            <h2 class="mb-4 font-bold tracking-widest text-sm2 text-gray-550 print:font-normal">
              PROJECTS
            </h2>

            <section class="mb-4 break-inside-avoid">
              <header>
                <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                  <a href="https://github.com/ReubenMathew/DistributedSystemsPortfolio" class="group">
                    Distributed Systems Portfolio
                    <span
                      class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                  </a>
                </h3>
                <!-- <p class="leading-normal text-md text-gray-650">
                  Found on GitHub
                </p> -->
              </header>
              <p class="mt-2 text-md text-gray-700 leading-normal">
                An example of a web application that leverages distributed systems technologies.
              </p>
              <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  NuxtJS
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Figma
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Python
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Flask
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Redis
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Axios
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Gunicorn
                </li>  
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Kubernetes
                </li>  
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Docker
                </li> 
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Postman
                </li>      
              </ul>
            </section>

          </div>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="https://github.com/ReubenMathew/DocScanner" class="group">
                  DocScanner
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
              </h3>
              <!-- <p class="leading-normal text-md text-gray-650">
                Found on GitHub
              </p> -->
            </header>
            <p class="mt-2 text-md text-gray-700 leading-normal">
              A simple web application based document scanner utilizing an OpenCV Edge Detection Engine.
            </p>
            <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Python
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Flask
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  OpenCV
                </li>
                <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                  Numpy
                </li>
              </ul>
          </section>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="https://github.com/ReubenMathew/DataOpsExperiments" class="group">
                  Machine Learning Experiments
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
              </h3>
              <!-- <p class="leading-normal text-md text-gray-650">
                Found on GitHub
              </p> -->
            </header>
            <p class="mt-2 text-md text-gray-700 leading-normal">
              Exploration and practice with various machine learning techniques and tools.
            </p>
            <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                PyTorch
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                NLP
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                Scikit-learn
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                Tensorflow
              </li>
            </ul>
          </section>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="https://github.com/EECS2311-Team8/SoftwareDevelopmentProject" class="group">
                  VennFX
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
              </h3>
              <!-- <p class="leading-normal text-md text-gray-650">
                Found on GitHub
              </p> -->
            </header>
            <p class="mt-2 text-md text-gray-700 leading-normal">
              Desktop application of a customizable venn diagram maker.
            </p>
            <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                Java
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                JavaFX
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                CircleCI
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                Gradle
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                JUnit
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                TestFX 
              </li>
            </ul>
          </section>

          <section class="mb-4 break-inside-avoid">
            <header>
              <h3 class="text-lg font-semibold text-gray-700 leading-snugish">
                <a href="https://business-template.now.sh/" class="group">
                  Business Frontend Template
                  <span
                    class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                </a>
              </h3>
              <!-- <p class="leading-normal text-md text-gray-650">
                Found on GitHub
              </p> -->
            </header>
            <p class="mt-2 text-md text-gray-700 leading-normal">
              A modern web template meant for businesses or financial firms.
            </p>
            <ul class="my-2 mb-6 flex flex-wrap text-md leading-relaxed">
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                JavaScript
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                VueJS
              </li>
              <li class="px-3 mr-2 mt-2 text-base text-gray-750 print:bg-white print:border-inset bg-gray-200">
                TailwindCSS
              </li>
            </ul>
          </section>


        </section>



        <section class="mt-8">

          <!-- To keep in the same column -->
          <div class="break-inside-avoid">

            <h2 class="mb-4 font-bold tracking-widest  text-sm2 text-gray-550 print:font-normal">
              CONTACT
            </h2>

            <section class="mb-4 break-inside-avoid">
              <ul class="list-inside pr-7">
                <li class="mt-2 leading-normal text-gray-700 text-md">
                  <a href="//reubenninan.tech" class="group">
                      reubenninan.tech
                    <span
                      class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                  </a>
                </li>
                <li class="mt-2 leading-normal text-gray-700 text-md">
                  <a href="//twitter.com/NinanReuben" class="group">
                    twitter.com/NinanReuben
                    <span
                      class="inline-block text-gray-550 print:text-black font-normal group-hover:text-gray-700 transition duration-100 ease-in">↗</span>
                  </a>
                </li>
                <li class="mt-2 leading-normal text-gray-700 text-md">
                  Toronto, Ontario
                </li>
                <li class="mt-2 leading-normal text-gray-700 text-md">
                  reubenninan@outlook.com
                </li>
              </ul>
            </section>

          </div>

        </section>

      </div>
      <!-- end Column -->



    </div>
  </div>
</template>