<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Engineering Portfolio | Maker & Developer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .hero-gradient { background: linear-gradient(135deg, #1e293b 0%, #0f172a 100%); }
        .project-card:hover { transform: translateY(-5px); transition: all 0.3s ease; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 font-sans">

    <nav class="p-6 bg-white shadow-sm sticky top-0 z-50">
        <div class="max-w-6xl mx-auto flex justify-between items-center">
            <h1 class="text-xl font-bold tracking-tight text-blue-600 underline decoration-2">PORTFOLIO.SYS</h1>
            <div class="space-x-8 font-medium text-sm uppercase tracking-widest">
                <a href="#projects" class="hover:text-blue-600">Projects</a>
                <a href="#skills" class="hover:text-blue-600">Toolkit</a>
                <a href="mailto:your-email@example.com" class="bg-blue-600 text-white px-4 py-2 rounded">Contact</a>
            </div>
        </div>
    </nav>

    <header class="hero-gradient text-white py-24 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h2 class="text-5xl font-extrabold mb-4">Building at the Intersection of <span class="text-blue-400">Code & Hardware</span></h2>
            <p class="text-xl text-gray-300 leading-relaxed">Aspiring Engineer focused on 3D design, aerospace simulations, and social-impact robotics.</p>
        </div>
    </header>

    <section id="projects" class="py-20 px-6 max-w-6xl mx-auto">
        <h3 class="text-3xl font-bold mb-12 border-b-4 border-blue-600 inline-block">Featured Work</h3>
        
        <div class="grid md:grid-cols-2 gap-8">
            
            <div class="project-card bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm">
                <div class="h-48 bg-gray-200 flex items-center justify-center italic text-gray-500">[Add Uganda Image Here]</div>
                <div class="p-6">
                    <span class="text-xs font-bold text-blue-600 uppercase">Social Impact / CAD</span>
                    <h4 class="text-2xl font-bold mt-2">Prosthetics for Uganda</h4>
                    <p class="mt-3 text-gray-600">Developed functional, non-medical 3D printed prosthetics designed for high utility and low-cost manufacturing in developing regions.</p>
                    <div class="mt-4 flex gap-2">
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Onshape</span>
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">FDM Printing</span>
                    </div>
                </div>
            </div>

            <div class="project-card bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm">
                <div class="h-48 bg-gray-200 flex items-center justify-center italic text-gray-500">[Add Pwnagotchi Image Here]</div>
                <div class="p-6">
                    <span class="text-xs font-bold text-green-600 uppercase">Cybersecurity / Hardware</span>
                    <h4 class="text-2xl font-bold mt-2">Pwnagotchi Shell</h4>
                    <p class="mt-3 text-gray-600">A gamified WiFi auditing tool. Built a custom slim-profile enclosure using 3D CAD and integrated e-ink displays with Raspberry Pi hardware.</p>
                    <div class="mt-4 flex gap-2">
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Linux</span>
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Soldering</span>
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Python</span>
                    </div>
                </div>
            </div>

            <div class="project-card bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm">
                <div class="h-48 bg-gray-200 flex items-center justify-center italic text-gray-500">[Add Rocket Image Here]</div>
                <div class="p-6">
                    <span class="text-xs font-bold text-red-600 uppercase">Aerospace / Math</span>
                    <h4 class="text-2xl font-bold mt-2">American Rocketry Challenge</h4>
                    <p class="mt-3 text-gray-600">Led a team to design and simulate high-altitude rockets. Iterated on fin geometry and motor mounts using OpenRocket simulations.</p>
                    <div class="mt-4 flex gap-2">
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Physics Modeling</span>
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Simulations</span>
                    </div>
                </div>
            </div>

            <div class="project-card bg-white border border-gray-200 rounded-xl overflow-hidden shadow-sm">
                <div class="h-48 bg-gray-200 flex items-center justify-center italic text-gray-500">[Add Plane Image Here]</div>
                <div class="p-6">
                    <span class="text-xs font-bold text-purple-600 uppercase">Aviation / Manufacturing</span>
                    <h4 class="text-2xl font-bold mt-2">3D Printed RC Plane</h4>
                    <p class="mt-3 text-gray-600">Experimental aircraft design focusing on lightweight structural integrity and electronic component integration for remote flight.</p>
                    <div class="mt-4 flex gap-2">
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Electronics</span>
                        <span class="px-2 py-1 bg-gray-100 text-xs rounded">Aerodynamics</span>
                    </div>
                </div>
            </div>

        </div>
    </section>

    <section id="skills" class="bg-gray-100 py-20 px-6">
        <div class="max-w-4xl mx-auto text-center">
            <h3 class="text-3xl font-bold mb-8">Technical Toolkit</h3>
            <div class="flex flex-wrap justify-center gap-4 text-sm font-semibold">
                <div class="bg-white p-4 rounded shadow-sm w-32">Python</div>
                <div class="bg-white p-4 rounded shadow-sm w-32">Onshape</div>
                <div class="bg-white p-4 rounded shadow-sm w-32">OpenRocket</div>
                <div class="bg-white p-4 rounded shadow-sm w-32">C++</div>
                <div class="bg-white p-4 rounded shadow-sm w-32">Soldering</div>
                <div class="bg-white p-4 rounded shadow-sm w-32">3D Printing</div>
            </div>
        </div>
    </section>

    <footer class="py-10 text-center text-gray-500 text-sm">
        &copy; 2026 Engineering Portfolio | Designed for Impact
    </footer>

</body>
</html>
