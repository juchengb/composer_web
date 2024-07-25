
# original website
[WEBSITE](https://anniwei.com/)


## 使用字體
- 中文
[ChenYuluoyan-Thin](https://github.com/Chenyu-otf/chenyuluoyan_thin)

- 英文
Julius Sans One

## CIS
待確認


# Shared part
## HEAD
```HTML
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About - Wei An Ni Music</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <!-- Google font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Julius+Sans+One&display=swap">

    <style>
        @font-face {
            font-family: 'ChenYuluoyan-Thin';
            src: url('./fonts/ChenYuluoyan-Thin.ttf') format('truetype');
            font-weight: normal;
            font-style: normal;
        }

        body {
            font-family: 'Julius Sans One', sans-serif;
        }
    </style>
</head>
```
## HEADER
```HTML
<!-- HEADER NAME -->
<header class="flex justify-center items-center bg-gray-50 py-2.5 sm:px-3.5">
	<a href="./index.html" class="text-sm leading-6 text-gray-900 text-center hover:text-[#54533B]">
		<div>
			<span style="font-size: 1.8rem;" class="chinese-font">魏安妮</span><br>
			<span style="font-family: 'Julius Sans One'">An-Ni Wei | Composer</span>
		</div>
	</a>
</header>
```

## NAV BAR
```HTML
<!-- NAVBAR -->
<nav class="bg-gray-800">
	<div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
		<div class="relative flex h-16 items-center justify-between">
			<div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
				<!-- Mobile menu button-->
				<button type="button"
					class="relative inline-flex items-center justify-center rounded-md p-2 text-gray-400 hover:bg-gray-700 hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
					aria-controls="mobile-menu" aria-expanded="false">
					<span class="absolute -inset-0.5"></span>
					<span class="sr-only">Open main menu</span>
					<!-- Icon when menu is closed. Menu open: "hidden", Menu closed: "block" -->
					<svg class="block h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
						stroke="currentColor" aria-hidden="true">
						<path stroke-linecap="round" stroke-linejoin="round"
							d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
					</svg>
					<!-- Icon when menu is open. Menu open: "block", Menu closed: "hidden" -->
					<svg class="hidden h-6 w-6" fill="none" viewBox="0 0 24 24" stroke-width="1.5"
						stroke="currentColor" aria-hidden="true">
						<path stroke-linecap="round" stroke-linejoin="round" d="M6 18L18 6M6 6l12 12" />
					</svg>
				</button>
			</div>
			<div class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-center">
				<div class="flex flex-shrink-0 items-center">
					<img class="h-8 w-auto" src="https://tailwindui.com/img/logos/mark.svg?color=indigo&shade=500"
						alt="Your Company">
				</div>
				<div class="hidden sm:ml-6 sm:block">
					<div class="flex space-x-4">
						<!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
						<a href="#" class="rounded-md bg-gray-900 px-3 py-2 text-sm font-medium text-white"
							aria-current="page">About</a>
						<a href="#"
							class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Compositions</a>
						<a href="#"
							class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Upcoming</a>
						<a href="#"
							class="rounded-md px-3 py-2 text-sm font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Contact</a>
					</div>
				</div>
			</div>
		</div>
	</div>

	<!-- Mobile menu, show/hide based on menu state. -->
	<div class="sm:hidden" id="mobile-menu">
		<div class="space-y-1 px-2 pb-3 pt-2">
			<!-- Current: "bg-gray-900 text-white", Default: "text-gray-300 hover:bg-gray-700 hover:text-white" -->
			<a href="#" class="block rounded-md bg-gray-900 px-3 py-2 text-base font-medium text-white"
				aria-current="page">About</a>
			<a href="#"
				class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Compositions</a>
			<a href="#"
				class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Upcoming</a>
			<a href="#"
				class="block rounded-md px-3 py-2 text-base font-medium text-gray-300 hover:bg-gray-700 hover:text-white">Contact</a>
		</div>
	</div>
</nav>
```
## FOOTER
```HTML
<!-- FOOTER -->
<!-- FOOTER -->
<footer class="bg-gray-800 text-white mt-12">
	<div class="container mx-auto px-4 py-8">
		<div class="flex flex-wrap justify-between">
			<div class="w-full md:w-1/3 mb-6 md:mb-0">
				<h3 class="text-lg font-semibold mb-2">魏安妮 An-Ni Wei | Composer</h3>
				<p>c 2024 Wei An-Ni Music</p>
			</div>
			<div class="w-full md:w-1/3 mb-6 md:mb-0">
				<h3 class="text-lg font-semibold mb-2">Pages</h3>
				<ul>
					<li><a href="/about" class="hover:text-gray-300">About</a></li>
					<li><a href="/compositions" class="hover:text-gray-300">Compositions</a></li>
					<li><a href="/upcoming" class="hover:text-gray-300">Upcoming</a></li>
					<li><a href="/contact" class="hover:text-gray-300">Contact</a></li>
				</ul>
			</div>
			<div class="w-full md:w-1/3">
				<h3 class="text-lg font-semibold mb-2">Follow Me</h3>
				<a href="https://www.instagram.com/anniwei.music/" class="hover:text-gray-300">Instagram</a>
			</div>
		</div>
	</div>
</footer>
```