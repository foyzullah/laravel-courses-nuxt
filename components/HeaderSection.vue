<template>
    <header class="flex text-white h-16 justify-between items-center">
                <div class="flex items-center">
                    <a href="/" class="inline-block">
                      <img class="w-56" src="https://laravel-courses.com/img/logo.png?1.0" alt="Logo">
                    </a>
                    <nav class="hidden h-16 space-x-8 sm:-my-px sm:ml-10 sm:flex">
                        <a href="courses.html" class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-base font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none focus:text-gray-700 focus:border-gray-300 transition">Courses</a>
                        <a href="courses.html" class="inline-flex items-center px-1 pt-1 border-b-2 border-transparent text-base font-medium leading-5 text-gray-500 hover:text-gray-700 hover:border-gray-300 focus:outline-none focus:text-gray-700 focus:border-gray-300 transition">Books</a>
                    </nav>
                </div>
        
                <!--Signup login and search button-->
                <div class="flex items-center">
                    <div class="flex flex-1 items-center px-2 mr-6 justify-end">
                        <form action="" method="GET">
                          <div class="w-full first-letter:max-w-xs">
                            <label for="search" class="sr-only">Search</label>
                            <div class="relative">
                              <div class="pointer-events-none absolute inset-y-0 left-0 flex items-center pl-3">
                                <svg class="h-5 w-5 text-gray-400" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" aria-hidden="true">
                                  <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 100 11 5.5 5.5 0 000-11zM2 9a7 7 0 1112.452 4.391l3.328 3.329a.75.75 0 11-1.06 1.06l-3.329-3.328A7 7 0 012 9z" clip-rule="evenodd"></path>
                                </svg>
                              </div>
                              <input id="search" name="keyword" class="block w-full rounded border border-gray-300 bg-white py-2 pl-10 pr-3 leading-5 placeholder-gray-500 focus:border-indigo-500 focus:placeholder-gray-400 focus:outline-none focus:ring-1 focus:ring-indigo-500 sm:text-sm" placeholder="Search" type="search" required>
                            </div>
                          </div>
                        </form>
                      </div>
                    <a href="#" class="text-sm font-medium text-gray-500 hover:text-gray-900">Sign in</a>
                    <a href="#" class="ml-8 inline-flex items-center justify-center rounded border border-transparent bg-black px-4 py-2 text-sm font-medium text-white shadow-sm hover:bg-red-500">Sign up</a>
                </div>
            </header>
</template>