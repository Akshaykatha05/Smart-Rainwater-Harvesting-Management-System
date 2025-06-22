# Smart-Rainwater-Harvesting-Management-System

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Rainwater Harvesting Forecast Dashboard</title>
<link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css"
rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-800">
<header class="bg-green-700 text-white py-6 shadow-md">
<div class="max-w-7xl mx-auto px-4">
<h1 class="text-3xl font-bold">Rainwater Harvesting Forecast Dashboard</h1>
<p class="text-sm mt-1">Using LSTM & Genetic Algorithms for Water Resource
Optimization</p>
</div>
</header>
<main class="max-w-7xl mx-auto px-4 py-8 grid gap-6 grid-cols-1 md:grid-cols-2 lg:grid-cols-3">
<!-- Storage Status Card -->
<div class="bg-white shadow-md rounded-xl p-6">
<h2 class="text-xl font-semibold mb-2">Current Tank Storage</h2>
<p class="text-gray-600 mb-4">Storage Level: <span class="font-bold text-green-
700">73%</span></p>
<div class="w-full bg-gray-200 rounded-full h-4">
<div class="bg-green-600 h-4 rounded-full" style="width: 73%;"></div>
</div>
</div>
<!-- Rainfall Forecast Card -->
<div class="bg-white shadow-md rounded-xl p-6">
<h2 class="text-xl font-semibold mb-2">Rainfall Forecast (Next 7 Days)</h2>
<ul class="list-disc ml-5 text-sm text-gray-700">
<li>Day 1: 12mm</li>
<li>Day 2: 8mm</li>
<li>Day 3: 0mm</li>
<li>Day 4: 5mm</li>
<li>Day 5: 14mm</li>
<li>Day 6: 3mm</li>
<li>Day 7: 0mm</li>
</ul>
</div>
<!-- Recommendations -->
<div class="bg-white shadow-md rounded-xl p-6">
<h2 class="text-xl font-semibold mb-2">Usage Recommendations</h2>
<ul class="list-disc ml-5 text-sm text-gray-700">
<li>Delay garden watering to leverage forecasted rain.</li>
<li>Prioritize tank usage over municipal water for laundry.</li>
<li>Open overflow valves on Day 5 to prevent spill.</li>
</ul>
</div>
<!-- Embedded Visualization -->
<div class="col-span-1 md:col-span-2 lg:col-span-3 bg-white shadow-md rounded-xl p-6">
<h2 class="text-xl font-semibold mb-4">Water Usage & Rainfall Visualization</h2>
<div class="aspect-w-16 aspect-h-9">
<!-- Embed Tableau or Chart.js here -->
<iframe src="https://www.accuweather.com/" class="w-full h-96 border rounded"
frameborder="0"></iframe>
</div>
</div>
<!-- About the Project -->
<div class="col-span-1 md:col-span-2 lg:col-span-3 bg-white shadow-md rounded-xl p-6">
<h2 class="text-xl font-semibold mb-2">Project Overview</h2>
<p class="text-sm text-gray-700 mb-2">
This system forecasts rainwater availability using a machine learning LSTM model trained
on historical rainfall, catchment inflow, and usage data. It uses a genetic algorithm to optimize
storage and usage schedules. Users can visualize and act on this information via the dashboard.
</p>
<p class="text-sm text-gray-700">
<strong>Green Skills:</strong> Climate resilience, water optimization. <strong>Tech
Stack:</strong> Python, Keras, Tableau.
</p>
</div>
</main>
<footer class="bg-green-700 text-white text-sm text-center py-4">
© 2025 Smart Water Systems | Built with LSTM + Genetic Algorithms
</footer>
</body>
</html>
