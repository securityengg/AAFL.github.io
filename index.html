<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Adaptive Adversary Lifecycle Framework (AALF)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Warm Neutral Harmony -->
    <!-- Application Structure Plan: A tab-based SPA structure was chosen to logically segment the dense report content into manageable, user-driven sections: 'Overview', 'The AALF Framework', 'Threat Deep Dive', 'Framework Comparison', and 'Recommendations'. This is more usable than a long scroll, encouraging exploration. The core is an interactive HTML/CSS diagram of the AALF, where clicking a phase reveals detailed content. This interactivity is extended in the 'Threat Deep Dive' section, where selecting a threat visually highlights its impact across the AALF phases. This structure prioritizes user understanding and non-linear exploration over the linear format of the source report. -->
    <!-- Visualization & Content Choices: 
        - Report Info: The 9 AALF phases. Goal: Organize & Inform. Viz/Method: Interactive HTML/CSS flow diagram. Interaction: Click to display details. Justification: Visually represents the lifecycle and encourages deep exploration of each phase without overwhelming the user.
        - Report Info: Key statistics (threat increase, ransomware share, breach causes). Goal: Inform. Viz/Method: Chart.js Donut/Bar charts. Interaction: Tooltips on hover. Justification: Makes quantitative data more impactful and easier to digest than text.
        - Report Info: Mapping threats (AI, Ransomware) to AALF. Goal: Relationships. Viz/Method: Interactive highlighting on the AALF diagram coupled with dynamic text display. Interaction: Click threat button to update visualization. Justification: Clearly illustrates the practical application of the framework by showing the relationship between a threat and the lifecycle phases.
        - Report Info: Comparison of AALF, CKC, MITRE. Goal: Compare. Viz/Method: HTML/Tailwind-styled comparison table. Interaction: N/A, static display for clarity. Justification: Provides a clear, structured side-by-side analysis of the frameworks' features.
        - Library/Method: Chart.js for canvas-based charts, Vanilla JS for all interactions and state management. Tailwind CSS for styling. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body { font-family: 'Inter', sans-serif; }
        .chart-container { position: relative; width: 100%; max-width: 450px; margin-left: auto; margin-right: auto; height: 300px; max-height: 350px; }
        @media (min-width: 768px) { .chart-container { height: 350px; max-height: 400px; } }
        .nav-link { transition: all 0.3s ease; }
        .nav-link.active { color: #3b82f6; border-bottom-color: #3b82f6; }
        .nav-link:not(.active) { border-bottom-color: transparent; }
        .phase-item { transition: all 0.3s ease; cursor: pointer; }
        .phase-item:hover { transform: translateY(-4px); box-shadow: 0 4px 10px rgba(0,0,0,0.1); }
        .phase-item.active { background-color: #3b82f6; color: white; }
        .phase-item.highlighted { background-color: #f59e0b; color: white; }
        .threat-btn { transition: all 0.2s ease-in-out; }
        .threat-btn.active { background-color: #1e40af; color: white; }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">
    <div class="container mx-auto px-4 sm:px-6 lg:px-8 py-8">
        
        <header class="text-center mb-10">
            <h1 class="text-4xl md:text-5xl font-bold text-gray-900">Adaptive Adversary Lifecycle Framework</h1>
            <p class="mt-4 text-lg text-gray-600">An interactive guide to the AALF model for understanding modern cyber threats.</p>
        </header>

        <nav class="sticky top-0 bg-gray-50/80 backdrop-blur-sm z-10 mb-10 border-b border-gray-200">
            <ul class="flex justify-center space-x-4 sm:space-x-8 text-sm sm:text-base font-medium text-gray-600">
                <li><a href="#overview" class="nav-link block py-4 border-b-2">Overview</a></li>
                <li><a href="#framework" class="nav-link block py-4 border-b-2">The Framework</a></li>
                <li><a href="#deepdive" class="nav-link block py-4 border-b-2">Threat Deep Dive</a></li>
                <li><a href="#comparison" class="nav-link block py-4 border-b-2">Comparison</a></li>
                <li><a href="#recommendations" class="nav-link block py-4 border-b-2">Recommendations</a></li>
            </ul>
        </nav>

        <main>
            <section id="overview" class="content-section space-y-8">
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                    <h2 class="text-3xl font-bold text-gray-900 mb-4">A New Model for a New Era of Threats</h2>
                    <p class="text-gray-700 leading-relaxed mb-6">This section introduces the Adaptive Adversary Lifecycle Framework (AALF), a novel cybersecurity model designed for the granularity and flexibility required to understand modern cyberattacks. The AALF synthesizes the linear Cyber Kill Chain (CKC) and the behavioral taxonomy of MITRE ATT&CK to address the non-linear, adaptive nature of today's threats. Here, you can explore the key trends driving the need for this new framework and the core data points that highlight the escalating sophistication of cyberattacks in 2024-2025.</p>
                    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                        <div class="bg-blue-50 p-6 rounded-lg">
                             <h3 class="text-xl font-semibold text-blue-900 mb-2">Key Trends</h3>
                             <ul class="list-disc list-inside space-y-2 text-blue-800">
                                 <li>AI-Driven Attacks</li>
                                 <li>Sophisticated Ransomware</li>
                                 <li>Supply Chain Vulnerabilities</li>
                                 <li>Cloud Security Challenges</li>
                                 <li>Advanced Persistent Threats (APTs)</li>
                             </ul>
                        </div>
                        <div class="lg:col-span-2 bg-white rounded-lg p-6">
                            <h3 class="text-xl font-semibold text-gray-900 mb-4 text-center">Cloud Breach Root Causes (2024)</h3>
                            <div class="chart-container">
                                <canvas id="breachCausesChart"></canvas>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="framework" class="content-section hidden space-y-8">
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                    <h2 class="text-3xl font-bold text-gray-900 mb-2">Exploring the 9 Phases of AALF</h2>
                    <p class="text-gray-700 leading-relaxed mb-8">This is the core of the AALF model. The framework redefines an adversary's journey into nine interconnected phases with new, precise terminology to match the modern threat landscape. Click on any phase below to explore its detailed description, its relevance in the context of emerging threats like AI-powered attacks, and how it aligns with traditional frameworks like the CKC and MITRE ATT&CK. This interactive diagram allows for a deep, non-linear exploration of the full adversary lifecycle, from initial planning to final monetization.</p>
                    <div class="lg:flex lg:space-x-8">
                        <div id="phases-container" class="lg:w-1/3 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-1 gap-4 mb-8 lg:mb-0">
                        </div>
                        <div id="phase-details" class="lg:w-2/3 bg-gray-100 p-6 rounded-lg min-h-[300px]">
                            <p class="text-center text-gray-500 pt-20">Select a phase to see details.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section id="deepdive" class="content-section hidden space-y-8">
                 <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                    <h2 class="text-3xl font-bold text-gray-900 mb-2">Threat Deep Dive: AALF in Action</h2>
                    <p class="text-gray-700 leading-relaxed mb-8">This section demonstrates the practical application of the AALF by mapping major contemporary threats to its nine phases. Select a threat category—AI-Powered Attacks, Ransomware & Double Extortion, or Supply Chain Compromises—to see which AALF phases are most impacted. The diagram will highlight these key phases. Click on a highlighted phase to understand how that specific threat manifests, providing a clear, actionable view of the adversary's playbook for today's most damaging attacks.</p>
                    <div class="flex justify-center space-x-4 mb-8">
                        <button class="threat-btn bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-full" data-threat="ai">AI-Powered Attacks</button>
                        <button class="threat-btn bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-full" data-threat="ransomware">Ransomware</button>
                        <button class="threat-btn bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded-full" data-threat="supplychain">Supply Chain</button>
                        <button id="clear-threat" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4 rounded-full">Clear</button>
                    </div>
                    <div class="lg:flex lg:space-x-8">
                        <div id="phases-container-deepdive" class="lg:w-1/3 grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-1 gap-4 mb-8 lg:mb-0">
                        </div>
                        <div id="threat-details" class="lg:w-2/3 bg-gray-100 p-6 rounded-lg min-h-[300px]">
                             <p class="text-center text-gray-500 pt-20">Select a threat, then click a highlighted phase.</p>
                        </div>
                    </div>
                </div>
            </section>

            <section id="comparison" class="content-section hidden space-y-8">
                 <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                    <h2 class="text-3xl font-bold text-gray-900 mb-2">Framework Comparison</h2>
                    <p class="text-gray-700 leading-relaxed mb-8">To understand the value of AALF, it's useful to compare it against the foundational frameworks it builds upon. This section provides a side-by-side comparison of the Adaptive Adversary Lifecycle Framework (AALF), the Cyber Kill Chain (CKC), and MITRE ATT&CK across key attributes like scope, granularity, and flexibility. This analysis highlights how AALF addresses the "adaptation gap" left by previous models in the face of modern, non-linear attacks.</p>
                    <div class="overflow-x-auto">
                        <table class="w-full text-left border-collapse">
                            <thead>
                                <tr class="bg-gray-100">
                                    <th class="p-4 font-semibold text-sm text-gray-800 border-b border-gray-300">Attribute</th>
                                    <th class="p-4 font-semibold text-sm text-gray-800 border-b border-gray-300">Cyber Kill Chain (CKC)</th>
                                    <th class="p-4 font-semibold text-sm text-gray-800 border-b border-gray-300">MITRE ATT&CK</th>
                                    <th class="p-4 font-semibold text-sm text-blue-800 border-b-2 border-blue-500">AALF (Adaptive)</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr class="border-b border-gray-200">
                                    <td class="p-4 font-semibold">Progression</td>
                                    <td class="p-4 text-gray-700">Strictly Linear & Sequential</td>
                                    <td class="p-4 text-gray-700">Non-Linear, Flexible</td>
                                    <td class="p-4 text-gray-700 font-medium">Adaptive & Iterative</td>
                                </tr>
                                <tr class="bg-gray-50 border-b border-gray-200">
                                    <td class="p-4 font-semibold">Granularity</td>
                                    <td class="p-4 text-gray-700">Macro-Level (7-8 Stages)</td>
                                    <td class="p-4 text-gray-700">Micro-Level (Tactics, Techniques)</td>
                                    <td class="p-4 text-gray-700 font-medium">Hybrid (9 Phases with micro-level detail)</td>
                                </tr>
                                <tr class="border-b border-gray-200">
                                    <td class="p-4 font-semibold">Scope</td>
                                    <td class="p-4 text-gray-700">Perimeter, Payload-centric</td>
                                    <td class="p-4 text-gray-700">Comprehensive (Enterprise, Cloud, Mobile)</td>
                                    <td class="p-4 text-gray-700 font-medium">Full Lifecycle (Pre-engagement to Post-monetization)</td>
                                </tr>
                                 <tr class="bg-gray-50 border-b border-gray-200">
                                    <td class="p-4 font-semibold">Focus</td>
                                    <td class="p-4 text-gray-700">External Threats, Malware</td>
                                    <td class="p-4 text-gray-700">Adversary Behavior (TTPs)</td>
                                    <td class="p-4 text-gray-700 font-medium">Evolving Adversary Lifecycle</td>
                                </tr>
                                <tr class="border-b border-gray-200">
                                    <td class="p-4 font-semibold">Modern Threats</td>
                                    <td class="p-4 text-gray-700">Limited coverage (e.g., file-less)</td>
                                    <td class="p-4 text-gray-700">Extensive but can lack context</td>
                                    <td class="p-4 text-gray-700 font-medium">Specifically designed for AI, non-linear attacks</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                 </div>
            </section>

            <section id="recommendations" class="content-section hidden space-y-8">
                <div class="bg-white p-8 rounded-xl shadow-sm border border-gray-200">
                    <h2 class="text-3xl font-bold text-gray-900 mb-2">Strategic Recommendations</h2>
                    <p class="text-gray-700 leading-relaxed mb-8">The AALF is more than a theoretical model; it's a tool for driving strategic action. This final section provides key, actionable recommendations for organizations to bolster their defenses against the threats analyzed in this report. These recommendations are aligned with the AALF's lifecycle approach, covering everything from proactive behavioral defense and identity management to comprehensive incident response planning. Use this as a guide to shift your security posture from reactive to proactive and resilient.</p>
                    <div class="grid md:grid-cols-2 gap-6">
                        <div class="bg-green-50 p-6 rounded-lg border border-green-200">
                             <h3 class="text-xl font-semibold text-green-900 mb-2">Proactive Defense</h3>
                             <ul class="list-disc list-inside space-y-2 text-green-800">
                                <li>Adopt Behavioral-Centric Defense (EDR/NDR)</li>
                                <li>Strengthen Identity & Access Management (MFA, Zero Trust)</li>
                                <li>Enhance Supply Chain Security Posture</li>
                                <li>Invest in AI-Aware Defensive Capabilities</li>
                             </ul>
                        </div>
                        <div class="bg-yellow-50 p-6 rounded-lg border border-yellow-200">
                             <h3 class="text-xl font-semibold text-yellow-900 mb-2">Resilience & Response</h3>
                             <ul class="list-disc list-inside space-y-2 text-yellow-800">
                                <li>Prioritize Data Protection & Recovery</li>
                                <li>Foster Continuous Security Awareness & Training</li>
                                <li>Develop & Test Comprehensive Incident Response Plans</li>
                                <li>Integrate Actionable Threat Intelligence</li>
                             </ul>
                        </div>
                    </div>
                </div>
            </section>
        </main>

    </div>

    <script>
        const aalfData = {
            phases: [
                { id: 1, name: "Pre-Engagement Scrutiny", short: "Recon & Resource Dev", desc: "In this initial phase, adversaries engage in both active and passive intelligence gathering on potential targets. This includes identifying vulnerabilities, profiling key personnel, mapping network configurations, and discerning existing security measures. Concurrently, they develop and acquire the necessary resources—such as custom tools, command-and-control infrastructure, and convincing synthetic personas—to support future malicious operations.", relevance: "This phase is increasingly critical as AI-driven OSINT capabilities and advanced persona generation techniques significantly enhance an attacker's ability to tailor subsequent, highly effective attacks." },
                { id: 2, name: "Infiltration Payload Crafting", short: "Weaponization & Initial Access", desc: "Based on the intelligence meticulously gathered during 'Pre-Engagement Scrutiny,' attackers proceed to create or obtain malicious payloads (e.g., bespoke malware, sophisticated exploits, weaponized documents) and meticulously design their initial access vectors. This includes the development of highly personalized, AI-generated phishing content.", relevance: "The advent of AI profoundly automates and personalizes phishing and social engineering attacks, rendering them exceptionally effective and difficult to detect. The observed shift by groups like Blind Eagle exemplifies the evolving nature of this phase." },
                { id: 3, name: "Operational Deployment", short: "Delivery & Execution", desc: "This phase marks the active transmission of the crafted malicious payload to the target environment. Upon successful delivery, its execution is triggered, often by exploiting identified vulnerabilities or through successful social engineering techniques. This phase also accounts for advanced techniques such as file-less malware and living-off-the-land attacks.", relevance: "This phase directly highlights the significant challenges posed by file-less malware and living-off-the-land attacks, which are designed to bypass conventional detection mechanisms. The use of intentionally corrupted documents to evade security tools is a recent example." },
                { id: 4, name: "Entrenchment & Ascent", short: "Installation & Escalation", desc: "Following initial compromise, adversaries focus on establishing and maintaining a persistent foothold within the compromised system or network. Concurrently, they actively seek to gain higher-level permissions and access. This involves installing backdoors, creating unauthorized accounts, or exploiting vulnerabilities to escalate privileges.", relevance: "This phase is absolutely crucial for enabling long-term compromise and extended adversarial operations. It is frequently where attackers leverage complex techniques like DLL search order hijacking or establish covert backdoors for future access." },
                { id: 5, name: "Stealth & Reconnaissance", short: "Defense Evasion & Discovery", desc: "Throughout the attack lifecycle, attackers employ a diverse array of methods to avoid detection by security mechanisms while simultaneously mapping and understanding the compromised environment. This includes sophisticated obfuscation techniques, anti-forensics measures, and active internal reconnaissance to map network structure.", relevance: "This phase profoundly emphasizes the non-linear and adaptive nature of modern attacks. AI-driven polymorphic malware constantly rewrites its code to circumvent signature-based defenses, making defense evasion significantly more challenging." },
                { id: 6, name: "Internal Expansion & Data Staging", short: "Lateral Movement & Collection", desc: "Once a foothold is established and stealth is maintained, adversaries systematically move deeper into the network, gaining access to additional systems and resources. Concurrently, they identify, gather, and organize data relevant to their ultimate objectives, often staging it in a central location before exfiltration.", relevance: "This phase underscores the critical importance of robust network segmentation. The Snowflake breach, for example, involved significant lateral movement and data collection after initial credential compromise." },
                { id: 7, name: "Remote Orchestration", short: "Command & Control", desc: "In this phase, attackers establish and maintain covert communication channels with their compromised systems. These channels are used to issue commands, receive exfiltrated data, and deliver further instructions, often designed to bypass firewalls and intrusion detection systems.", relevance: "This phase is paramount for maintaining persistent access and control over compromised assets. APT groups frequently leverage legitimate cloud services for their C2 infrastructure to evade detection." },
                { id: 8, name: "Objective Realization & Data Exfiltration", short: "Actions & Exfil", desc: "This phase represents the culmination of the attack, where the adversary carries out their primary, predefined goal. This can encompass a wide range of actions, including mass data theft, data destruction, systemic disruption, or encryption of data for ransom, along with the systematic exfiltration of data.", relevance: "This phase directly manifests the tangible impact of attacks, such as the widespread encryption and data theft seen in major ransomware incidents. Supply chain attacks can lead to profound and cascading operational disruptions." },
                { id: 9, name: "Value Extraction & Trace Eradication", short: "Monetization & Cleanup", desc: "This final, often overlooked, phase involves adversaries undertaking activities to derive financial or strategic value from the attack. This includes demanding ransom payments or selling exfiltrated data. Concurrently, attackers attempt to remove forensic evidence, delete logs, or eliminate backdoors to hinder investigation.", relevance: "This extended phase is crucial for understanding the full economic impact of modern attacks, particularly double extortion ransomware. The sale of data from the Snowflake breach on dark web forums is a direct example." }
            ],
            threats: {
                ai: {
                    name: "AI-Powered Attacks",
                    highlight: [1, 2, 3, 4, 5, 8],
                    details: {
                        1: "AI tools automate OSINT collection and generate convincing synthetic identities for long-term social engineering campaigns.",
                        2: "Generative AI crafts highly personalized phishing content, including deepfake audio/video, making them nearly indistinguishable from legitimate communications.",
                        3: "AI is used to develop polymorphic malware that constantly rewrites its own code to evade signature-based detection.",
                        4: "AI-powered tools accelerate brute-force credential attacks and password guessing by learning user behavior patterns, facilitating rapid account takeovers.",
                        5: "Adversarial AI/ML techniques are used to actively disrupt or confuse defensive AI systems, allowing attackers to evade detection.",
                        8: "AI-driven ransomware can analyze victim data to create 'tailor-made' ransom demands, optimizing the amount for maximum payment likelihood."
                    }
                },
                ransomware: {
                    name: "Ransomware & Double Extortion",
                    highlight: [1, 2, 3, 6, 8, 9],
                    details: {
                        1: "Ransomware groups conduct reconnaissance to identify vulnerable, high-value organizations in sectors like healthcare and critical infrastructure.",
                        2: "Ransomware-as-a-Service (RaaS) models lower the barrier to entry, making it easy for affiliates to obtain and weaponize devastating ransomware strains.",
                        3: "Social engineering via email remains a primary delivery vector. The Change Healthcare attack involved impersonating IT support to gain initial network credentials.",
                        6: "A defining characteristic of double extortion is the exfiltration of sensitive data BEFORE encryption. In the Change Healthcare breach, 6 terabytes of PII were stolen.",
                        8: "This phase involves the mass encryption of critical files and systems, leading to massive operational disruption, as seen in the CDK Global and Change Healthcare incidents.",
                        9: "Ransom demands are issued, and exfiltrated data is sold on dark web marketplaces, creating multiple revenue streams for attackers."
                    }
                },
                supplychain: {
                    name: "Supply Chain Compromises",
                    highlight: [1, 2, 3, 6, 8, 9],
                    details: {
                        1: "Attackers identify widely used software or service providers (like Snowflake) where a single compromise can grant access to hundreds of downstream clients.",
                        2: "Initial access is often gained via compromised credentials from customers' employees, harvested through infostealer malware campaigns.",
                        3: "Compromised credentials are used to log into legitimate accounts, bypassing MFA where it is not enforced, providing immediate entry.",
                        6: "Attackers move laterally within the provider's environment, accessing and exfiltrating vast amounts of data from numerous distinct customer tenants.",
                        8: "The primary objective is large-scale data theft. The Snowflake incident involved exfiltrating records from over 100 customer environments.",
                        9: "The stolen data from multiple organizations is advertised and sold on cybercrime forums, with threat actors extorting victims for payment."
                    }
                }
            }
        };

        document.addEventListener('DOMContentLoaded', () => {
            const navLinks = document.querySelectorAll('.nav-link');
            const sections = document.querySelectorAll('.content-section');
            const phasesContainer = document.getElementById('phases-container');
            const phaseDetails = document.getElementById('phase-details');
            
            const phasesContainerDeepdive = document.getElementById('phases-container-deepdive');
            const threatDetails = document.getElementById('threat-details');
            const threatBtns = document.querySelectorAll('.threat-btn');
            const clearThreatBtn = document.getElementById('clear-threat');

            let activePhase = null;
            let activeThreat = null;
            let activeDeepDivePhase = null;

            function initPhases(container, clickHandler) {
                container.innerHTML = '';
                aalfData.phases.forEach(phase => {
                    const phaseEl = document.createElement('div');
                    phaseEl.className = 'phase-item bg-white p-4 rounded-lg shadow-sm border border-gray-200';
                    phaseEl.dataset.phaseId = phase.id;
                    phaseEl.innerHTML = `<div class="flex items-center space-x-3">
                        <span class="flex-shrink-0 bg-blue-100 text-blue-600 font-bold w-10 h-10 rounded-full flex items-center justify-center">${phase.id}</span>
                        <div>
                            <p class="font-semibold text-gray-900">${phase.name}</p>
                            <p class="text-sm text-gray-500">${phase.short}</p>
                        </div>
                    </div>`;
                    phaseEl.addEventListener('click', () => clickHandler(phase.id));
                    container.appendChild(phaseEl);
                });
            }

            function handlePhaseClick(phaseId) {
                activePhase = phaseId;
                const phaseData = aalfData.phases.find(p => p.id === phaseId);
                phaseDetails.innerHTML = `
                    <h3 class="text-2xl font-bold text-gray-900 mb-3 flex items-center">
                        <span class="flex-shrink-0 bg-blue-500 text-white font-bold w-8 h-8 rounded-full flex items-center justify-center mr-3">${phaseData.id}</span>
                        ${phaseData.name}
                    </h3>
                    <div class="space-y-4">
                        <div>
                            <h4 class="font-semibold text-lg text-gray-800">Description</h4>
                            <p class="text-gray-700 leading-relaxed">${phaseData.desc}</p>
                        </div>
                        <div>
                            <h4 class="font-semibold text-lg text-gray-800">Modern Relevance</h4>
                            <p class="text-gray-700 leading-relaxed">${phaseData.relevance}</p>
                        </div>
                    </div>
                `;
                updateActivePhase(phasesContainer, phaseId);
            }
            
            function handleDeepDivePhaseClick(phaseId) {
                if (!activeThreat || !aalfData.threats[activeThreat].highlight.includes(phaseId)) return;
                
                activeDeepDivePhase = phaseId;
                const threatData = aalfData.threats[activeThreat];
                const phaseData = aalfData.phases.find(p => p.id === phaseId);

                threatDetails.innerHTML = `
                    <h3 class="text-2xl font-bold text-gray-900 mb-3 flex items-center">
                         <span class="flex-shrink-0 bg-amber-500 text-white font-bold w-8 h-8 rounded-full flex items-center justify-center mr-3">${phaseData.id}</span>
                        ${phaseData.name}
                    </h3>
                    <div class="space-y-4">
                        <div>
                            <h4 class="font-semibold text-lg text-gray-800">Impact of ${threatData.name}</h4>
                            <p class="text-gray-700 leading-relaxed">${threatData.details[phaseId]}</p>
                        </div>
                    </div>
                `;
                updateActivePhase(phasesContainerDeepdive, phaseId, true);
            }

            function updateActivePhase(container, phaseId, isDeepDive = false) {
                 container.querySelectorAll('.phase-item').forEach(p => {
                    p.classList.remove('active');
                    if (parseInt(p.dataset.phaseId) === phaseId) {
                        p.classList.add('active');
                    }
                });
            }

            function handleThreatClick(threatKey) {
                activeThreat = threatKey;
                activeDeepDivePhase = null;
                const threatData = aalfData.threats[threatKey];

                threatBtns.forEach(btn => {
                    btn.classList.remove('active');
                    if(btn.dataset.threat === threatKey) {
                        btn.classList.add('active');
                    }
                });

                phasesContainerDeepdive.querySelectorAll('.phase-item').forEach(p => {
                    p.classList.remove('highlighted', 'active', 'opacity-50');
                    const phaseId = parseInt(p.dataset.phaseId);
                    if (threatData.highlight.includes(phaseId)) {
                        p.classList.add('highlighted');
                    } else {
                        p.classList.add('opacity-50');
                    }
                });

                threatDetails.innerHTML = `<div class="text-center pt-16">
                    <h3 class="text-xl font-bold mb-2">${threatData.name}</h3>
                    <p class="text-gray-600">This threat significantly impacts the highlighted phases. Click on a highlighted phase to see specific details.</p>
                </div>`;
            }

            clearThreatBtn.addEventListener('click', () => {
                activeThreat = null;
                activeDeepDivePhase = null;
                 threatBtns.forEach(btn => btn.classList.remove('active'));
                phasesContainerDeepdive.querySelectorAll('.phase-item').forEach(p => {
                    p.classList.remove('highlighted', 'active', 'opacity-50');
                });
                threatDetails.innerHTML = `<p class="text-center text-gray-500 pt-20">Select a threat, then click a highlighted phase.</p>`;
            });

            function updateActiveNav() {
                let currentSection = 'overview';
                sections.forEach(section => {
                    const rect = section.getBoundingClientRect();
                    if (rect.top <= 150 && rect.bottom >= 150) {
                        currentSection = section.id;
                    }
                });
                navLinks.forEach(link => {
                    link.classList.remove('active');
                    if (link.getAttribute('href') === '#' + currentSection) {
                        link.classList.add('active');
                    }
                });
            }

            navLinks.forEach(link => {
                link.addEventListener('click', e => {
                    e.preventDefault();
                    const targetId = link.getAttribute('href').substring(1);
                    document.querySelectorAll('.content-section').forEach(s => s.classList.add('hidden'));
                    document.getElementById(targetId).classList.remove('hidden');

                    navLinks.forEach(l => l.classList.remove('active'));
                    link.classList.add('active');
                });
            });

            document.querySelectorAll('.nav-link')[0].click();
            
            initPhases(phasesContainer, handlePhaseClick);
            initPhases(phasesContainerDeepdive, handleDeepDivePhaseClick);

            threatBtns.forEach(btn => {
                btn.addEventListener('click', () => handleThreatClick(btn.dataset.threat));
            });

            const breachCtx = document.getElementById('breachCausesChart').getContext('2d');
            new Chart(breachCtx, {
                type: 'doughnut',
                data: {
                    labels: ['Misconfigurations', 'Human Error', 'Lack of MFA'],
                    datasets: [{
                        label: 'Cloud Breach Causes',
                        data: [51, 31, 17],
                        backgroundColor: [
                            'rgba(59, 130, 246, 0.8)',
                            'rgba(245, 158, 11, 0.8)',
                            'rgba(239, 68, 68, 0.8)'
                        ],
                        borderColor: [
                            'rgba(59, 130, 246, 1)',
                            'rgba(245, 158, 11, 1)',
                            'rgba(239, 68, 68, 1)'
                        ],
                        borderWidth: 1
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { position: 'bottom' },
                        tooltip: { callbacks: { label: (context) => `${context.label}: ${context.raw}%` } }
                    }
                }
            });
        });
    </script>
</body>
</html>
