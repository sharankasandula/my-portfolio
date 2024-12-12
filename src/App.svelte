<script>
  let darkMode = false;

  // Toggle dark mode
  function toggleDarkMode() {
    darkMode = !darkMode;
    if (darkMode) {
      document.documentElement.classList.add("dark");
    } else {
      document.documentElement.classList.remove("dark");
    }
  }
</script>

<div class={darkMode ? "dark" : ""}>
  <div
    class="font-sans bg-gray-100 dark:bg-gray-900 dark:text-white text-gray-800"
  >
    <div class="container mx-auto py-8 space-y-8 min-h-screen flex flex-col">
      <header class="container mx-auto py-8">
        <nav>
          <ul>
            <li>
              <a href="/" class="flex items-center gap-2 hover:underline">
                <img class=" h-6 w-6" src="./sjklogo.svg" alt="SJK Logo" />
                <span>Sharan Kasandula</span>
              </a>
            </li>
          </ul>
        </nav>
      </header>

      <main class="container mx-auto flex-grow py-8">
        <div class="gap-6 grid grid-cols-1 md:grid-cols-3">
          <div
            class="flex flex-col gap-4 md:col-span-2 md:flex-row md:gap-6 bg-white dark:bg-gray-800 p-6 rounded-lg shadow"
          >
            <img
              class="flex-shrink-0 h-32 w-32 object-cover rounded-full"
              src="./sharan.png"
              alt="Headshot of Sharan Kasandula"
            />
            <div class="flex flex-col justify-center md:gap-1">
              <h2 class="text-2xl font-bold">Hi! I'm Sharan</h2>
              <p>
                A Software Developer at
                <a
                  class="text-blue-600 hover:underline"
                  href="https://beyondscale.tech/">BeyondScale</a
                >
              </p>
              <div
                class="border border-gray-300 dark:border-gray-600 flex gap-2 items-center md:mt-2 mt-4 px-3 py-1 rounded-lg self-start"
              >
                <svg
                  class="h-6 w-6"
                  fill="none"
                  version="1.1"
                  stroke="currentColor"
                  xmlns="http://www.w3.org/2000/svg"
                  xmlns:xlink="http://www.w3.org/1999/xlink"
                  viewBox="0 0 54.757 54.757"
                  xml:space="preserve"
                >
                  <g>
                    <path
                      d="M27.557,12c-3.859,0-7,3.141-7,7s3.141,7,7,7s7-3.141,7-7S31.416,12,27.557,12z M27.557,24c-2.757,0-5-2.243-5-5
		s2.243-5,5-5s5,2.243,5,5S30.314,24,27.557,24z"
                    />
                    <path
                      d="M40.94,5.617C37.318,1.995,32.502,0,27.38,0c-5.123,0-9.938,1.995-13.56,5.617c-6.703,6.702-7.536,19.312-1.804,26.952
		L27.38,54.757L42.721,32.6C48.476,24.929,47.643,12.319,40.94,5.617z M41.099,31.431L27.38,51.243L13.639,31.4
		C8.44,24.468,9.185,13.08,15.235,7.031C18.479,3.787,22.792,2,27.38,2s8.901,1.787,12.146,5.031
		C45.576,13.08,46.321,24.468,41.099,31.431z"
                    />
                  </g>
                </svg>
                <p class="text-sm">Based in Hyderabad</p>
              </div>
            </div>
          </div>

          <!-- Resume Card -->
          <div
            class="flex flex-col h-full md:gap-1 bg-white dark:bg-gray-800 p-6 rounded-lg shadow"
          >
            <h2 class="text-2xl font-bold">Resume</h2>
            <p>4+ years in software design and development</p>
            <a
              href="https://drive.google.com/file/d/1jdiQmin17c_wZKElhN_6vECBl3almpr1/view"
              target="_blank"
              class="text-blue-600 flex flex-row gap-2 hover:underline hover:underline-offset-4 md:mt-auto mt-4 w-fit"
            >
              <svg
                class="h-6 w-6"
                fill="none"
                stroke-width="1.5"
                stroke="currentColor"
                viewBox="0 0 24 24"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  d="M3 16.5v2.25A2.25 2.25 0 0 0 5.25 21h13.5A2.25 2.25 0 0 0 21 18.75V16.5M16.5 12 12 16.5m0 0L7.5 12m4.5 4.5V3"
                ></path>
              </svg>
              Download my resume
            </a>
            <a
              href="/resume.html"
              target="_blank"
              class="text-blue-600 flex flex-row gap-2 hover:underline hover:underline-offset-4 md:mt-auto mt-4 w-fit"
            >
              <svg
                class="h-6 w-6 text-blue-600"
                viewBox="0 0 24 24"
                fill="none"
                stroke="currentColor"
              >
                <path
                  d="M3 15H21M3 19H13M21 7H13M21 11H13M4.6 11H7.4C7.96005 11 8.24008 11 8.45399 10.891C8.64215 10.7951 8.79513 10.6422 8.89101 10.454C9 10.2401 9 9.96005 9 9.4V6.6C9 6.03995 9 5.75992 8.89101 5.54601C8.79513 5.35785 8.64215 5.20487 8.45399 5.10899C8.24008 5 7.96005 5 7.4 5H4.6C4.03995 5 3.75992 5 3.54601 5.10899C3.35785 5.20487 3.20487 5.35785 3.10899 5.54601C3 5.75992 3 6.03995 3 6.6V9.4C3 9.96005 3 10.2401 3.10899 10.454C3.20487 10.6422 3.35785 10.7951 3.54601 10.891C3.75992 11 4.03995 11 4.6 11Z"
                  stroke="currenColor"
                  stroke-width="2"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                />
              </svg>
              View my resume
            </a>
          </div>
          <!-- Projects -->
          <!-- <a
            href="/work/covetrus.html"
            class="bento-project block bg-white dark:bg-moss900 p-4 rounded-lg shadow hover:shadow-lg transition"
          >
            <img
              src="/Covetrus-Thumbnail.f0c12bda.png"
              alt="Thumbnail of Covetrus project"
              class="rounded-md mb-3"
            />
            <div class="flex flex-col gap-1">
              <h2 class="text-xl font-semibold">Covetrus</h2>
              <p>Minimising risk to safety for veterinary staff</p>
            </div>
          </a>

          <a
            href="/work/vocal.html"
            class="bento-project block bg-white dark:bg-moss900 p-4 rounded-lg shadow hover:shadow-lg transition"
          >
            <img
              src="/Vocal-Thumbnail.6f2cb97e.png"
              alt="Thumbnail of Vocal project"
              class="rounded-md mb-3"
            />
            <div class="flex flex-col gap-1">
              <h2 class="text-xl font-semibold">Vocal</h2>
              <p>Connecting writers with their readers</p>
            </div>
          </a>

          <a
            href="/work/go1.html"
            class="bento-project block bg-white dark:bg-moss900 p-4 rounded-lg shadow hover:shadow-lg transition"
          >
            <img
              src="/go1-Thumbnail.63c26031.png"
              alt="Thumbnail of Go1 project"
              class="rounded-md mb-3"
            />
            <div class="flex flex-col gap-2">
              <h2 class="text-xl font-semibold">go1</h2>
              <p>Insights on learning trends for employers</p>
            </div>
          </a> -->

          <!-- Social Links -->
          <div class="gap-4 grid md:grid-cols-2">
            <a
              href="https://www.xing.com/profile/Sharan_Kasandula/"
              target="_blank"
              class="bg-white dark:bg-gray-800 p-4 rounded-lg flex items-center gap-2 hover:shadow transition justify-center"
            >
              <svg
                fill="#000000"
                version="1.1"
                class="h-6 w-6"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                viewBox="0 0 512 512"
                xml:space="preserve"
              >
                <path
                  style="display: inline; fill-rule: evenodd; clip-rule: evenodd;"
                  d="M309.215,304.749
		c30.414,57.874,62.227,114.961,94.801,173.782c4.402,7.997,11.826,19.137,8.67,26.073c-4.242,9.332-25.275,5.539-41.855,5.539
		c-19.523,0-36.902,3.53-49.764-0.799c-13.125-4.416-25.002-36.989-31.6-48.979c-27.934-50.773-57.736-105.254-85.319-154.831
		c47.294-86.353,103.108-180.979,152.448-270.165c7.572-13.661,13.748-33.771,31.613-34.769C396.68,0.14,413.596,1.4,430.875,1.4
		c14.32,0,36.428-2.108,40.295,3.941c6.6,10.367-10.842,30.466-15.807,39.51C407.158,132.44,356.971,217.997,309.215,304.749z
		 M125.953,357.67c15.657-1.908,23.653-23.777,30.789-36.341c22.631-39.746,45.697-80.715,66.369-117.705
		c-12.774-23.728-29.766-51.385-44.249-76.624c-6.25-10.891-10.979-25.087-25.263-25.275c-25.275,0-50.575,0-75.85,0
		c-4.129,0.586-7.846,1.635-8.682,5.527c-2.046,12.438,5.625,19.486,9.48,26.073c8.97,15.407,17.978,29.866,27.646,46.608
		c3.094,5.327,12.874,18.938,12.625,24.489c-0.15,3.718-7.598,12.638-10.254,17.378c-21.607,38.586-39.334,70.735-60.83,109.009
		c-3.194,5.689-10.267,12.301-7.896,20.534c1.023,3.605,6.749,6.637,9.469,6.325C74.853,357.67,100.403,357.67,125.953,357.67z"
                >
                </path>
              </svg>
              Xing
            </a>
            <a
              href="https://www.linkedin.com/in/sharan-kasandula-233663a2/"
              target="_blank"
              class="bg-white dark:bg-gray-800 p-4 rounded-lg flex items-center gap-2 hover:shadow transition justify-center md:row-span-2"
            >
              <svg viewBox="0 0 24 24" class="h-6 w-6"
                ><path
                  d="M21 4.324v15.353A1.323 1.323 0 0 1 19.677 21H4.324A1.323 1.323 0 0 1 3 19.677V4.324A1.324 1.324 0 0 1 4.324 3h15.353A1.323 1.323 0 0 1 21 4.324ZM8.294 9.882H5.647v8.47h2.647v-8.47Zm.238-2.911a1.525 1.525 0 0 0-1.514-1.536h-.047a1.535 1.535 0 0 0 0 3.07 1.525 1.525 0 0 0 1.561-1.487v-.047Zm9.82 6.236c0-2.546-1.62-3.536-3.229-3.536a3.017 3.017 0 0 0-2.678 1.366h-.074V9.882H9.882v8.47h2.647v-4.504a1.757 1.757 0 0 1 1.589-1.896h.1c.842 0 1.467.53 1.467 1.864v4.537h2.647l.02-5.146Z"
                ></path></svg
              >
              LinkedIn
            </a>
            <a
              href="https://github.com/sharankasandula"
              target="_blank"
              class="bg-white dark:bg-gray-800 p-4 rounded-lg flex items-center gap-2 hover:shadow transition justify-center"
            >
              <svg viewBox="0 0 24 24" class="h-6 w-6"
                ><path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M12.008 2.167C6.474 2.167 2 6.674 2 12.249c0 4.457 2.867 8.23 6.843 9.565.498.1.68-.217.68-.484 0-.233-.017-1.035-.017-1.87-2.784.602-3.364-1.201-3.364-1.201-.447-1.169-1.11-1.47-1.11-1.47-.911-.617.067-.617.067-.617 1.01.067 1.54 1.035 1.54 1.035.895 1.536 2.337 1.102 2.917.835.083-.651.348-1.102.63-1.352-2.22-.234-4.557-1.102-4.557-4.975 0-1.102.397-2.003 1.027-2.704-.1-.25-.447-1.286.1-2.671 0 0 .845-.267 2.75 1.035a9.623 9.623 0 0 1 2.502-.334c.845 0 1.707.117 2.502.334 1.906-1.302 2.75-1.035 2.75-1.035.548 1.385.2 2.42.1 2.67.647.702 1.028 1.603 1.028 2.705 0 3.873-2.337 4.724-4.574 4.975.365.317.68.918.68 1.87 0 1.351-.017 2.436-.017 2.77 0 .267.183.585.68.484A10.075 10.075 0 0 0 22 12.25c.016-5.575-4.474-10.082-9.992-10.082Z"
                ></path></svg
              >
              Github
            </a>
          </div>

          <!-- Contact Card -->
          <div
            class="flex flex-col md:col-span-2 md:gap-1 bg-white dark:bg-gray-800 p-6 rounded-lg shadow"
          >
            <h2 class="text-2xl font-bold">Get in touch</h2>
            <p class="text-sm">
              I'm always open to new opportunities and collaborations. Feel free
              to reach out!
            </p>
            <a
              href="mailto:sharankasandula@gmail.com"
              target="_blank"
              class="bg-blue-600 text-white inline-flex items-center justify-center w-fit py-2 px-4 rounded-full hover:bg-blue-700 transition md:mt-auto"
            >
              <svg width="20" height="20" class="mr-3">
                <path
                  fill-rule="evenodd"
                  clip-rule="evenodd"
                  d="M5.632 2.5h8.736c.67 0 1.224 0 1.675.037.469.038.9.12 1.304.326.627.32 1.137.83 1.456 1.457.2.39.283.805.323 1.254.044.137.052.28.026.417.015.375.015.81.015 1.308V12.7c0 .67 0 1.224-.037 1.675-.038.469-.12.9-.327 1.304a3.334 3.334 0 0 1-1.456 1.457c-.405.206-.835.288-1.304.326-.45.037-1.004.037-1.675.037H5.632c-.67 0-1.224 0-1.675-.037-.469-.038-.9-.12-1.304-.326a3.333 3.333 0 0 1-1.456-1.457c-.206-.405-.289-.835-.327-1.303-.037-.452-.037-1.005-.037-1.676V7.3c0-.499 0-.933.015-1.308a.833.833 0 0 1 .026-.417c.04-.45.124-.864.323-1.254.32-.627.83-1.137 1.456-1.457.405-.206.835-.288 1.304-.326C4.407 2.5 4.96 2.5 5.632 2.5ZM2.5 7.434v5.233c0 .713 0 1.199.031 1.574.03.365.084.552.15.682.16.314.415.569.729.729.13.066.317.12.683.15.375.03.86.031 1.574.031h8.666c.714 0 1.2 0 1.575-.031.365-.03.552-.084.682-.15.314-.16.569-.415.728-.729.067-.13.12-.317.15-.682.031-.375.032-.86.032-1.574V7.434l-5.493 3.845-.096.067c-.454.319-.852.599-1.306.712a2.5 2.5 0 0 1-1.21 0c-.454-.113-.852-.393-1.306-.712l-.096-.067L2.5 7.434Zm14.931-1.986-6.38 4.466c-.607.425-.736.498-.85.527a.833.833 0 0 1-.403 0c-.113-.029-.242-.102-.85-.527L2.57 5.448c.03-.173.068-.285.113-.371.16-.314.414-.569.728-.729.13-.066.317-.12.683-.15.375-.03.86-.031 1.574-.031h8.666c.714 0 1.2 0 1.575.031.365.03.552.084.682.15.314.16.569.415.728.729.044.086.083.198.113.37Z"
                ></path>
              </svg>
              Drop me a message
            </a>
          </div>
        </div>
      </main>

      <footer class="container mx-auto text-center text-xs mt-8 py-4">
        <p>
          Designed and built with love by Sharan using
          <a
            class="text-blue-600 hover:underline"
            href="https://svelte.dev"
            target="_blank">Svelte</a
          >
          and
          <a
            class="text-blue-600 hover:underline"
            target="_blank"
            href="https://tailwindcss.com">Tailwind</a
          >
        </p>
      </footer>
    </div>
  </div>
</div>
