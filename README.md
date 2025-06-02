<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAYHAN KABIR - Freelance Business Development & Research</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* Light blue-gray */
            color: #334155; /* Darker text */
        }
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 0.5rem;
            margin-bottom: 2rem;
        }
        .section-heading::after {
            content: '';
            position: absolute;
            left: 0;
            bottom: 0;
            width: 50%;
            height: 4px;
            background-color: #6366f1; /* Indigo */
            border-radius: 9999px;
        }
        .loading-spinner {
            border: 4px solid #f3f3f3; /* Light grey */
            border-top: 4px solid #6366f1; /* Blue */
            border-radius: 50%;
            width: 24px;
            height: 24px;
            animation: spin 1s linear infinite;
            display: inline-block;
            vertical-align: middle;
            margin-left: 8px;
        }
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="antialiased">

    <header class="bg-white shadow-md py-4">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-indigo-700 rounded-md p-2 hover:bg-indigo-50 transition-colors">RAYHAN KABIR Freelancing</a>
            <nav class="hidden md:flex space-x-6">
                <a href="#services" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Services</a>
                <a href="#portfolio" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Portfolio</a>
                <a href="#about" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">About</a>
                <a href="#contact" class="text-gray-600 hover:text-indigo-700 font-medium transition-colors">Contact</a>
            </nav>
            <button class="md:hidden text-gray-600 hover:text-indigo-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
            </button>
        </div>
    </header>

    <section class="bg-gradient-to-r from-indigo-600 to-purple-700 text-white py-20 px-4 rounded-b-lg shadow-lg">
        <div class="container mx-auto text-center">
            <h1 class="text-5xl md:text-6xl font-extrabold mb-4 leading-tight">
                Accelerate Your Growth with Expert <br class="hidden md:inline"> Business & Research Solutions
            </h1>
            <p class="text-xl md:text-2xl mb-8 max-w-3xl mx-auto opacity-90">
                Specializing in Business Development, Lead Generation, and In-depth Industry Research for ambitious companies.
            </p>
            <a href="#contact" class="bg-white text-indigo-700 hover:bg-indigo-100 font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105">
                Let's Discuss Your Project
            </a>
        </div>
    </section>

    <section id="services" class="py-16 px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 section-heading mx-auto">My Services</h2>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-10">

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 border border-gray-100">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-1.28-8.455-3.245m16.91 0c.75-.405 1.4-.903 1.96-1.474m-1.96 1.474a8.732 8.732 0 01-14.77-1.473m14.77 1.473L19.5 10.5m-14.77 1.473L4.5 10.5m-2.245-3.245a23.931 23.931 0 0112-2.755c3.183 0 6.22 1.28 8.455 3.245m-16.91 0c-.75.405-1.4.903-1.96 1.474m1.96-1.474A8.732 8.732 0 0112 3c-3.183 0-6.22 1.28-8.455 3.245M12 15v2.25m-4.5-4.5H9m9 0h-2.25"></path></svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Business Development</h3>
                    <p class="text-gray-600 leading-relaxed service-description" id="bd-description">
                        I help businesses identify new opportunities, build strategic partnerships, and optimize sales processes to achieve sustainable growth. From market entry strategies to expanding your client base, I provide actionable insights and execution support.
                    </p>
                    <button class="mt-4 bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full text-sm transition-colors duration-300 enhance-btn" data-target="bd-description">
                        ✨ Enhance Description
                    </button>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 border border-gray-100">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"></path></svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Targeted Lead Generation</h3>
                    <p class="text-gray-600 leading-relaxed service-description" id="lg-description">
                        Fuel your sales pipeline with high-quality, qualified leads. I specialize in identifying your ideal customer profiles, building robust databases, and executing effective outreach campaigns across various channels to connect you with decision-makers.
                    </p>
                    <button class="mt-4 bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full text-sm transition-colors duration-300 enhance-btn" data-target="lg-description">
                        ✨ Enhance Description
                    </button>

                    <div class="mt-8 pt-6 border-t border-gray-200">
                        <h4 class="text-xl font-semibold mb-3 text-gray-800">✨ Get Lead Strategy Ideas</h4>
                        <p class="text-gray-600 text-sm mb-4">Describe your target industry or client type to get tailored lead generation strategies.</p>
                        <input type="text" id="lead-strategy-input" class="shadow appearance-none border rounded-md w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent mb-3" placeholder="e.g., 'SaaS companies in healthcare'">
                        <button id="generate-lead-strategy-btn" class="bg-purple-600 hover:bg-purple-700 text-white font-bold py-2 px-4 rounded-full text-sm transition-colors duration-300">
                            ✨ Suggest Strategies
                        </button>
                        <div id="lead-strategy-output" class="mt-4 p-4 bg-gray-100 rounded-md text-gray-700 text-sm hidden">
                            <div class="loading-spinner hidden" id="lead-strategy-spinner"></div>
                            <p id="lead-strategy-text"></p>
                        </div>
                    </div>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 border border-gray-100">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H2m20 0h-3.25l-.5-1.5c-.14-.42-.62-.65-.98-.35l-4.5 3.5-4.5-3.5c-.36-.3-.84-.07-.98.35l-.5 1.5H2M12 8l-3 3m0 0l-3-3m3 3V3"></path></svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">American Football Research</h3>
                    <p class="text-gray-600 leading-relaxed service-description" id="afr-description">
                        Dive deep into the world of American football with comprehensive research services. From player performance analysis and scouting reports to historical data trends and strategic insights, I provide the data you need to gain a competitive edge.
                    </p>
                    <button class="mt-4 bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full text-sm transition-colors duration-300 enhance-btn" data-target="afr-description">
                        ✨ Enhance Description
                    </button>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 border border-gray-100">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01"></path></svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Pharmacy Company Research</h3>
                    <p class="text-gray-600 leading-relaxed service-description" id="pcr-description">
                        Navigate the complex pharmaceutical landscape with expert research. I offer services including market trend analysis, competitive intelligence, drug pipeline tracking, regulatory insights, and specialized data scraping from manufacturing pharma companies, particularly those using papertrain methods.
                    </p>
                    <button class="mt-4 bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full text-sm transition-colors duration-300 enhance-btn" data-target="pcr-description">
                        ✨ Enhance Description
                    </button>
                </div>

                <div class="bg-white p-8 rounded-xl shadow-lg hover:shadow-xl transition-shadow duration-300 border border-gray-100">
                    <div class="text-indigo-500 mb-4">
                        <svg class="w-12 h-12" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m-1 4h1m8-10h1m-1 4h1m-1 4h1m-8 4v2m8-2v2"></path></svg>
                    </div>
                    <h3 class="text-2xl font-semibold mb-4 text-gray-800">Company-Specific Research (e.g., Hudl, Lumitos AG, Apprentice)</h3>
                    <p class="text-gray-600 leading-relaxed service-description" id="csr-description">
                        Need deep insights into specific companies like Hudl, Lumitos AG, or Apprentice? I conduct detailed analyses of their market position, product offerings, strategic initiatives, and potential for collaboration or competitive intelligence, including expertise in Salesforce for companies like Lumitos AG.
                    </p>
                    <button class="mt-4 bg-indigo-500 hover:bg-indigo-600 text-white font-semibold py-2 px-4 rounded-full text-sm transition-colors duration-300 enhance-btn" data-target="csr-description">
                        ✨ Enhance Description
                    </button>
                </div>

            </div>
        </div>
    </section>

    <section id="portfolio" class="bg-gray-50 py-16 px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 section-heading mx-auto">My Work & Case Studies</h2>
            <div class="text-center text-gray-600 max-w-2xl mx-auto">
                <p class="mb-6">
                    Here you'll find examples of how I've helped clients achieve their goals. Due to the confidential nature of some projects, specific client names and sensitive data are anonymized, but the impact and results are clear.
                </p>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                    <div class="bg-white p-6 rounded-xl shadow-md border border-gray-100">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Case Study: Boosting SaaS Lead Pipeline</h3>
                        <p class="text-gray-600 mb-4">
                            Developed and executed a targeted lead generation strategy for a B2B SaaS company, resulting in a <strong>30% increase in qualified leads</strong> within 3 months and a <strong>15% improvement in conversion rates</strong>.
                        </p>
                        <a href="#" class="text-indigo-600 hover:underline font-medium">Read More (Coming Soon)</a>
                    </div>
                    <div class="bg-white p-6 rounded-xl shadow-md border border-gray-100">
                        <h3 class="text-xl font-semibold mb-2 text-gray-800">Case Study: Pharmaceutical Market Entry Analysis</h3>
                        <p class="text-gray-600 mb-4">
                            Conducted comprehensive market research for a pharmaceutical startup, identifying key market segments, competitive landscape, and regulatory hurdles, which informed their successful product launch strategy.
                        </p>
                        <a href="#" class="text-indigo-600 hover:underline font-medium">Read More (Coming Soon)</a>
                    </div>
                </div>
                <p class="mt-8">
                    More detailed case studies and project examples are available upon request.
                </p>
            </div>
        </div>
    </section>

    <section id="about" class="py-16 px-4">
        <div class="container mx-auto text-center max-w-4xl">
            <h2 class="text-4xl font-bold mb-12 section-heading mx-auto">About Me</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="md:w-1/3 mb-8 md:mb-0">
                    <img src="RKA.jpeg" alt="RAYHAN KABIR Professional Headshot" class="rounded-full mx-auto shadow-lg w-48 h-48 object-cover">
                </div>
                <div class="md:w-2/3 text-left">
                    <p class="text-lg text-gray-700 leading-relaxed mb-4">
                        With a strong background in strategic business development and a passion for uncovering critical insights, I help organizations thrive in competitive landscapes. My expertise spans identifying new growth avenues, optimizing lead generation processes, and providing in-depth research across diverse industries.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Whether it's analyzing American football statistics to gain a strategic edge, dissecting the complexities of the pharmaceutical market, or providing targeted intelligence on companies like Hudl, Lumitos AG, and Apprentice, I am dedicated to delivering data-driven solutions that drive tangible results for my clients. I combine analytical rigor with a proactive approach to help you make informed decisions and achieve your business objectives.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="testimonials" class="bg-indigo-50 py-16 px-4">
        <div class="container mx-auto">
            <h2 class="text-4xl font-bold text-center mb-12 section-heading mx-auto">What Clients Say</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <div class="bg-white p-6 rounded-xl shadow-md border border-gray-100">
                    <p class="text-gray-700 italic mb-4">
                        "The lead generation strategy provided was exceptional. We saw an immediate increase in qualified prospects and a clear path to converting them into customers. Highly recommend!"
                    </p>
                    <p class="font-semibold text-gray-800">- Jane Doe, Marketing Director at Tech Solutions Inc.</p>
                </div>
                <div class="bg-white p-6 rounded-xl shadow-md border border-gray-100">
                    <p class="text-gray-700 italic mb-4">
                        "Their research on the pharmaceutical market was incredibly detailed and insightful. It gave us the confidence to make crucial strategic decisions."
                    </p>
                    <p class="font-semibold text-gray-800">- John Smith, CEO of Pharma Innovations LLC</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="py-16 px-4">
        <div class="container mx-auto max-w-3xl">
            <h2 class="text-4xl font-bold text-center mb-12 section-heading mx-auto">Get in Touch</h2>
            <p class="text-lg text-center text-gray-700 mb-8">
                Ready to discuss your next project? Fill out the form below or reach out directly.
            </p>
            <form class="bg-white p-8 rounded-xl shadow-lg border border-gray-100">
                <div class="mb-6">
                    <label for="name" class="block text-gray-700 text-sm font-bold mb-2">Name</label>
                    <input type="text" id="name" name="name" class="shadow appearance-none border rounded-md w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Your Name">
                </div>
                <div class="mb-6">
                    <label for="email" class="block text-gray-700 text-sm font-bold mb-2">Email</label>
                    <input type="email" id="email" name="email" class="shadow appearance-none border rounded-md w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="your.email@example.com">
                </div>
                <div class="mb-6">
                    <label for="subject" class="block text-gray-700 text-sm font-bold mb-2">Subject</label>
                    <input type="text" id="subject" name="subject" class="shadow appearance-none border rounded-md w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Project Inquiry, Collaboration, etc.">
                </div>
                <div class="mb-6">
                    <label for="message" class="block text-gray-700 text-sm font-bold mb-2">Message</label>
                    <textarea id="message" name="message" rows="6" class="shadow appearance-none border rounded-md w-full py-3 px-4 text-gray-700 leading-tight focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:border-transparent" placeholder="Tell me about your project and how I can help..."></textarea>
                </div>
                <div class="text-center">
                    <button type="submit" class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105 focus:outline-none focus:ring-2 focus:ring-indigo-500 focus:ring-offset-2">
                        Send Message
                    </button>
                </div>
            </form>
            <div class="text-center mt-8">
                <p class="text-gray-600">You can also connect with me on:</p>
                <div class="flex justify-center space-x-6 mt-4">
                    <a href="https://www.linkedin.com/in/rayhan-kabir-anik-0549a1117/" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition-colors">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    </a>
                    <a href="https://www.facebook.com/rayhankabir.anik" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition-colors">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M22.675 0h-21.35c-.732 0-1.325.593-1.325 1.325v21.351c0 .732.593 1.325 1.325 1.325h11.351v-9.294h-3.13v-3.622h3.13v-2.19c0-3.102 1.893-4.788 4.659-4.788 1.325 0 2.463.099 2.795.143v3.24l-1.918.001c-1.504 0-1.795.715-1.795 1.763v2.313h3.587l-.467 3.622h-3.12v9.293h6.075c.732 0 1.325-.593 1.325-1.325v-21.35c0-.732-.593-1.325-1.325-1.325z"/></svg>
                    </a>
                    <a href="https://www.instagram.com/rayhankabir8225/" target="_blank" class="text-indigo-600 hover:text-indigo-800 transition-colors">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.07 1.645.07 4.85s-.012 3.584-.07 4.85c-.148 3.252-1.691 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07s-3.584-.012-4.85-.07c-3.252-.148-4.771-1.691-4.919-4.919-.058-1.265-.07-1.644-.07-4.85s.012-3.584.07-4.85c.148-3.252 1.691-4.771 4.919-4.919 1.265-.058 1.644-.07 4.85-.07zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948s.014 3.668.072 4.948c.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.073 4.948.073s3.668-.014 4.948-.072c4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948s-.014-3.667-.072-4.947c-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.162 6.162 6.162 6.162-2.759 6.162-6.162-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.791-4-4s1.791-4 4-4 4 1.791 4 4-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/></svg>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-white py-8 px-4 rounded-t-lg shadow-inner">
        <div class="container mx-auto text-center text-sm">
            <p>&copy; 2025 RAYHAN KABIR. All rights reserved.</p>
            <div class="mt-2 space-x-4">
                <a href="#services" class="hover:underline">Services</a>
                <a href="#portfolio" class="hover:underline">Portfolio</a>
                <a href="#about" class="hover:underline">About</a>
                <a href="#contact" class="hover:underline">Contact</a>
            </div>
        </div>
    </footer>

    <script>
        // Function to call the Gemini API
        async function callGeminiAPI(prompt, outputElement, spinnerElement) {
            outputElement.classList.add('hidden'); // Hide previous output
            spinnerElement.classList.remove('hidden'); // Show spinner

            let chatHistory = [];
            chatHistory.push({ role: "user", parts: [{ text: prompt }] });
            const payload = { contents: chatHistory };
            const apiKey = ""; // Canvas will automatically provide the API key at runtime

            const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.0-flash:generateContent?key=${apiKey}`;

            try {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                const result = await response.json();

                if (result.candidates && result.candidates.length > 0 &&
                    result.candidates[0].content && result.candidates[0].content.parts &&
                    result.candidates[0].content.parts.length > 0) {
                    const text = result.candidates[0].content.parts[0].text;
                    outputElement.textContent = text;
                } else {
                    outputElement.textContent = "Error: Could not generate content. Please try again.";
                }
            } catch (error) {
                console.error("Error calling Gemini API:", error);
                outputElement.textContent = "Error: Failed to connect to the AI service. Please try again later.";
            } finally {
                spinnerElement.classList.add('hidden'); // Hide spinner
                outputElement.classList.remove('hidden'); // Show output
            }
        }

        // Service Description Enhancer Logic
        document.querySelectorAll('.enhance-btn').forEach(button => {
            button.addEventListener('click', async (event) => {
                const targetId = event.target.dataset.target;
                const descriptionElement = document.getElementById(targetId);
                const originalText = descriptionElement.textContent.trim();

                // Create a temporary spinner element for the button
                const spinner = document.createElement('span');
                spinner.className = 'loading-spinner';
                event.target.appendChild(spinner);
                event.target.disabled = true; // Disable button during loading

                const prompt = `Enhance the following freelance service description to be more persuasive and professional, focusing on benefits for the client. Keep it concise, around 60-80 words, and maintain the core meaning:\n\n"${originalText}"`;

                // Use a temporary element to display the enhanced text before replacing
                const tempOutputElement = document.createElement('p');
                tempOutputElement.style.display = 'none'; // Keep it hidden initially

                try {
                    await callGeminiAPI(prompt, tempOutputElement, spinner);
                    descriptionElement.textContent = tempOutputElement.textContent; // Replace original text
                } catch (error) {
                    console.error("Error enhancing description:", error);
                    // Optionally, revert to original text or show an error message in the description area
                } finally {
                    event.target.removeChild(spinner); // Remove spinner
                    event.target.disabled = false; // Re-enable button
                }
            });
        });

        // Lead Generation Strategy Suggester Logic
        document.getElementById('generate-lead-strategy-btn').addEventListener('click', async () => {
            const industryInput = document.getElementById('lead-strategy-input').value.trim();
            const outputDiv = document.getElementById('lead-strategy-output');
            const outputText = document.getElementById('lead-strategy-text');
            const spinner = document.getElementById('lead-strategy-spinner');

            if (!industryInput) {
                outputText.textContent = "Please enter a target industry or client type.";
                outputDiv.classList.remove('hidden');
                return;
            }

            const prompt = `Generate 3-5 concise and actionable lead generation strategies for a business targeting "${industryInput}". Focus on diverse approaches. Format as a bulleted list.`;

            await callGeminiAPI(prompt, outputText, spinner);
        });
    </script>

</body>
</html>
