<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://unpkg.com/tailwindcss@^1.0/dist/tailwind.min.css" rel="stylesheet">
    <title>Document</title>
</head>
<body>
    <header class="text-red-600 body-font">
        <div class="container mx-auto flex flex-wrap p-5 flex-col md:flex-row items-center">
          <a class="flex title-font font-medium items-center text-red-900 mb-4 md:mb-0">
            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                <path d="M12.378 1.602a.75.75 0 00-.756 0L3 6.632l9 5.25 9-5.25-8.622-5.03zM21.75 7.93l-9 5.25v9l8.628-5.032a.75.75 0 00.372-.648V7.93zM11.25 22.18v-9l-9-5.25v8.57a.75.75 0 00.372.648l8.628 5.033z" />
              </svg>
              
            <span class="ml-3 text-xl">Snooker Club</span>
          </a>
          <nav class="md:mr-auto md:ml-4 md:py-1 md:pl-4 md:border-l md:border-red-400	flex flex-wrap items-center text-base justify-center">
            <a href="/" class="mr-5 hover:text-red-900">Home</a>
            <a href="/" class="mr-5 hover:text-red-900">Membership</a>
            <a href="/" class="mr-5 hover:text-red-900">Reservation and Booking</a>
            <a href="/" class="mr-5 hover:text-red-900">Tournments and Events</a>
            <a href="/" class="mr-5 hover:text-red-900">forum</a>
            <a href="/" class="mr-5 hover:text-red-900">coaching class</a>
          </nav>
          <button class="inline-flex items-center bg-red-100 border-0 py-1 px-3 focus:outline-none hover:bg-red-200 rounded text-base mt-4 md:mt-0">Enroll now
            <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-1" viewBox="0 0 24 24">
              <path d="M5 12h14M12 5l7 7-7 7"></path>
            </svg>
          </button>
        </div>
      </header> 
      <hr>
      <section class="text-red-600 body-font">
        <div class="container mx-auto flex px-5 py-24 md:flex-row flex-col items-center">
          <div class="lg:flex-grow md:w-1/2 lg:pr-24 md:pr-16 flex flex-col md:items-start md:text-left mb-16 md:mb-0 items-center text-center">
            <h1 class="title-font sm:text-4xl text-3xl mb-4 font-medium text-red-900">Welcome To Snooker Club
              
            </h1>
            <p class="mb-8 leading-relaxed">Welcome to our premier snooker club, where cue sports enthusiasts come together to indulge in the art of precision and strategy. Whether you're a seasoned player aiming to finesse your skills or a novice eager to learn the ropes, our state-of-the-art facilities cater to players of all levels. Immerse yourself in the classic green baize, meticulously maintained tables, and an atmosphere buzzing with friendly competition. Join us in our passion for the centuries-old game of snooker, where every shot is a masterpiece in the making. Experience camaraderie, refine your technique, and make your mark in the world of snooker at our club.</p>
            
          </div>
          <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
            <img class="object-cover object-center rounded" alt="hero" src="https://source.unsplash.com/720x600/?snooker">
          </div>
        </div>
      </section>
      <hr>
      <section class="text-red-600 body-font overflow-hidden">
        <div class="container px-5 py-24 mx-auto">
          <div class="lg:w-4/5 mx-auto flex flex-wrap">
            <img alt="feature" class="lg:w-1/3 w-full lg:h-auto h-64 object-cover object-center rounded" src="https://source.unsplash.com/400x400/?snooker">
            <div class="lg:w-1/2 w-full lg:pl-10 lg:py-6 mt-6 lg:mt-0">
              <h1 class="text-red-900 text-3xl title-font font-medium mb-1">Join Our Snooker Community</h1>
              <p class="leading-relaxed">When you become a member of the Snooker Club, you're not just joining a club; you're becoming a part of a passionate snooker community. Connect with fellow snooker enthusiasts, participate in tournaments, and receive exclusive access to our top-notch facilities. Whether you're a casual player or a professional, our club provides the perfect environment to hone your snooker skills and enjoy the game to the fullest.</p>
              
            </div>
          </div>
        </div>
      </section>
      <hr>
      <section class="text-red-600 body-font">
        <div class="container px-5 py-24 mx-auto">
          <div class="lg:w-2/3 flex flex-col sm:flex-row sm:items-center items-start mx-auto">
            <h1 class="flex-grow sm:pr-16 text-2xl font-medium title-font text-red-900">Pricing Plans</h1>
            <button class="flex-shrink-0 text-red-900 bg-red-100 border-0 py-2 px-8 focus:outline-none hover:bg-red-200 hover:text-red-600 rounded text-lg mt-10 sm:mt-0">Learn More</button>
          </div>
          <div class="flex flex-wrap -m-4">
            <div class="xl:w-1/4 md:w-1/2 p-4">
              <div class="border border-red-300 p-6 rounded-lg">
                <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-red-100 text-red-500 mb-4">
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
                    <path d="M22 12h-4l-3 9L9 3l-3 9H2"></path>
                  </svg>
                </div>
                <h2 class="text-lg text-red-900 font-medium title-font mb-2">Starter</h2>
                <p class="leading-relaxed text-base">Perfect for beginners and casual players.</p>
                <a class="mt-3 text-red-500 inline-flex items-center">Learn More
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7"></path>
                  </svg>
                </a>
              </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
              <div class="border border-red-300 p-6 rounded-lg">
                <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-red-100 text-red-500 mb-4">
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
                    <circle cx="6" cy="6" r="3"></circle>
                    <circle cx="6" cy="18" r="3"></circle>
                    <line x1="20" y1="4" x2="8.12" y2="15.88"></line>
                    <line x1="14.47" y1="14.48" x2="20" y2="20"></line>
                    <line x1="8.12" y1="8.12" x2="12" y2="12"></line>
                  </svg>
                </div>
                <h2 class="text-lg text-red-900 font-medium title-font mb-2">Intermediate</h2>
                <p class="leading-relaxed text-base">Suitable for players with some experience.</p>
                <a class="mt-3 text-red-500 inline-flex items-center">Learn More
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7"></path>
                  </svg>
                </a>
              </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
              <div class="border border-red-300 p-6 rounded-lg">
                <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-red-100 text-red-500 mb-4">
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
                    <circle cx="6" cy="6" r="3"></circle>
                    <circle cx="6" cy="18" r="3"></circle>
                    <line x1="20" y1="4" x2="8.12" y2="15.88"></line>
                    <line x1="14.47" y1="14.48" x2="20" y2="20"></line>
                    <line x1="8.12" y1="8.12" x2="12" y2="12"></line>
                  </svg>
                </div>
                <h2 class="text-lg text-red-900 font-medium title-font mb-2">Advanced</h2>
                <p class="leading-relaxed text-base">For skilled players looking to compete at a higher level.</p>
                <a class="mt-3 text-red-500 inline-flex items-center">Learn More
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7"></path>
                  </svg>
                </a>
              </div>
            </div>
            <div class="xl:w-1/4 md:w-1/2 p-4">
              <div class="border border-red-300 p-6 rounded-lg">
                <div class="w-10 h-10 inline-flex items-center justify-center rounded-full bg-red-100 text-red-500 mb-4">
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-6 h-6" viewBox="0 0 24 24">
                    <circle cx="6" cy="6" r="3"></circle>
                    <circle cx="6" cy="18" r="3"></circle>
                    <line x1="20" y1="4" x2="8.12" y2="15.88"></line>
                    <line x1="14.47" y1="14.48" x2="20" y2="20"></line>
                    <line x1="8.12" y1="8.12" x2="12" y2="12"></line>
                  </svg>
                </div>
                <h2 class="text-lg text-red-900 font-medium title-font mb-2">Professional</h2>
                <p class="leading-relaxed text-base">Designed for serious players aiming for professional level.</p>
                <a class="mt-3 text-red-500 inline-flex items-center">Learn More
                  <svg fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-4 h-4 ml-2" viewBox="0 0 24 24">
                    <path d="M5 12h14M12 5l7 7-7 7"></path>
                  </svg>
                </a>
              </div>
            </div>
          </div>
        </div>
      </section>
    </body>
</html>
