<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Crypto Alpha AI | AI-Powered Crypto Intelligence</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;600;800&family=Space+Grotesk:wght@400;600;700&family=DM+Sans:wght@400;500;700&family=IBM+Plex+Mono:wght@400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        cyber: {
                            cyan: '#00f0ff',
                            purple: '#7928ca',
                            lime: '#c3ff00',
                            red: '#ff0050',
                            gray: '#161616',
                            dark: '#050505'
                        }
                    },
                    fontFamily: {
                        heading: ['Space Grotesk', 'sans-serif'],
                        orbitron: ['Orbitron', 'sans-serif'],
                        body: ['DM Sans', 'sans-serif'],
                        mono: ['IBM Plex Mono', 'monospace']
                    }
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .glow-text {
                text-shadow: 0 0 10px #00f0ff88;
            }
            .glow-box {
                box-shadow: 0 0 20px #00f0ff66;
            }
            .hero-bg {
                background-color: #050505;
                background-image: radial-gradient(circle at 30% 40%, #7928ca33 0px, transparent 4%),
                                  radial-gradient(circle at 70% 60%, #00f0ff33 0px, transparent 4%);
                background-size: 3px 3px;
            }
            .dash {
                background-image: repeating-linear-gradient(45deg, rgba(255,255,255,0.05), rgba(255,255,255,0.05) 1px, transparent 0, transparent 8px);
            }
        }
    </style>
</head>
<body class="bg-cyber-dark font-body text-gray-200">
    <!-- Header -->
    <header class="sticky top-0 z-50 bg-black bg-opacity-90 backdrop-blur-sm border-b border-cyber-gray">
        <nav class="container mx-auto px-4 py-4 flex justify-between items-center">
            <a href="#" class="font-heading font-bold text-2xl bg-gradient-to-r from-cyber-cyan to-cyber-purple bg-clip-text text-transparent">
                Crypto Alpha AI
            </a>
            <div class="hidden md:flex space-x-6">
                <a href="#how" class="hover:text-cyber-cyan transition">Features</a>
                <a href="#eve" class="hover:text-cyber-cyan transition">Eve</a>
                <a href="#pricing" class="hover:text-cyber-cyan transition">Pricing</a>
                <a href="#samples" class="hover:text-cyber-cyan transition">Samples</a>
            </div>
            <div class="flex items-center">
                <a href="#pricing" class="px-4 py-2 bg-cyber-purple mr-3 rounded-md hover:bg-cyber-cyan transition">Subscribe</a>
                <button class="md:hidden text-xl">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-bg border-b border-gray-800 py-24 md:py-32">
        <div class="container mx-auto px-4 flex flex-col md:flex-row items-center">
            <div class="md:w-1/2 mb-12 md:mb-0">
                <h1 class="text-4xl md:text-6xl font-orbitron font-bold mb-6 tracking-tighter">
                    <span class="block">AI-Crafted Crypto</span>
                    <span class="block bg-gradient-to-r from-cyber-cyan via-cyber-purple to-cyber-cyan bg-clip-text text-transparent py-1">
                        Reports in Your Inbox
                    </span>
                </h1>
                <p class="text-xl text-gray-300 mb-10 max-w-2xl">
                    No hype. Just alpha. Built for traders, founders, and VCs.
                </p>
                <div class="flex flex-wrap gap-3">
                    <a href="#pricing" class="px-8 py-4 bg-gradient-to-r from-cyber-purple via-cyan-500 to-emerald-500 rounded-md text-black font-bold flex items-center space-x-2 transform transition hover:scale-[1.03] glow-box">
                        <span>Subscribe</span>
                        <i class="fas fa-fire ml-1"></i>
                    </a>
                    <a href="#samples" class="px-8 py-4 border-2 border-cyber-purple rounded-md font-bold flex items-center space-x-2">
                        <span>View Sample Report</span>
                        <i class="fas fa-arrow-right"></i>
                    </a>
                </div>
                <div class="mt-12 bg-cyber-purple bg-opacity-10 border border-cyber-purple rounded-lg p-4 inline-block">
                    <p class="text-sm font-mono font-semibold flex items-center">
                        <i class="fas fa-trend-up text-cyber-cyan mr-2"></i>
                        Never Miss Alpha Again
                    </p>
                </div>
            </div>
            <div class="md:w-1/2">
                <div class="dash border border-gray-700 rounded-xl bg-gray-900 p-6 relative">
                    <div class="absolute -inset-2 -z-10 bg-cyber-dark rounded-2xl"></div>
                    <div class="flex space-x-2 mb-4">
                        <div class="w-3 h-3 bg-red-500 rounded-full"></div>
                        <div class="w-3 h-3 bg-yellow-500 rounded-full"></div>
                        <div class="w-3 h-3 bg-green-500 rounded-full"></div>
                    </div>
                    <div class="text-cyan-300">
                        <div class="font-mono text-sm">
                            <div class="text-lg mb-2 font-bold text-white">[Market Intelligence Report - ETH]</div>
                            <div class="mb-1"><span class="text-purple-300">// TLDDR </span> Accumulate ETH between $1600-$1750</div>
                            <div class="mb-1"><span class="text-purple-300">// SIGNAL</span> Whales shifting to ETH -> $250M inflow</div>
                            <div class="mb-1"><span class="text-purple-300">// INSIGHT</span> Catalyst: Proto-Danksharding EIP-4844</div>
                            <div><span class="text-purple-300">// ALERT</span> Funding rates turning +ve -> shorts squeezed</div>
                        </div>
                        <div class="mt-4 text-green-300">
                            <div>🔥 <span class="text-white">DeFi, Degen, Done Right</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- How It Works -->
    <section id="how" class="py-20 bg-gradient-to-t from-cyber-gray to-black">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-heading font-bold text-center mb-16">
                How It Works
            </h2>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Feature 1 -->
                <div class="border border-gray-700 bg-black bg-opacity-30 rounded-xl p-6 hover:border-cyber-cyan transition-colors">
                    <div class="text-cyber-cyan text-5xl mb-6 glow-text">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3 class="font-heading font-bold text-xl mb-3">Track Token Momentum</h3>
                    <p class="text-gray-400 mb-4">
                        We analyze 9D momentum signals across 1800+ tokens to spot emerging opportunities early.
                    </p>
                    <div class="mt-4 border-t border-gray-700 pt-4">
                        <div class="font-mono text-xs text-cyber-cyan flex items-center">
                            <i class="fas fa-bolt mr-2"></i>
                            Real-time signals on Uniswap volume bursts
                        </div>
                    </div>
                </div>
                
                <!-- Feature 2 -->
                <div class="border border-gray-700 bg-black bg-opacity-30 rounded-xl p-6 hover:border-cyber-cyan transition-colors">
                    <div class="text-cyber-purple text-5xl mb-6">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3 class="font-heading font-bold text-xl mb-3">Smart Money Alerts</h3>
                    <p class="text-gray-400 mb-4">
                        Track the wallets and patterns of 87 top-tier funds and traders for strategic advantage.
                    </p>
                    <div class="mt-4 border-t border-gray-700 pt-4">
                        <div class="font-mono text-xs text-cyber-purple flex items-center">
                            <i class="fas fa-bolt mr-2"></i>
                            VC fund movements detected 12-48h before DEX listings
                        </div>
                    </div>
                </div>
                
                <!-- Feature 3 -->
                <div class="border border-gray-700 bg-black bg-opacity-30 rounded-xl p-6 hover:border-cyber-cyan transition-colors">
                    <div class="text-cyber-cyan text-5xl mb-6">
                        <i class="fab fa-telegram"></i>
                    </div>
                    <h3 class="font-heading font-bold text-xl mb-3">AI Threads</h3>
                    <p class="text-gray-400 mb-4">
                        24/7 curated alpha feed with synthesized market insights delivered to Telegram.
                    </p>
                    <div class="mt-4 border-t border-gray-700 pt-4">
                        <div class="font-mono text-xs text-cyber-lime flex items-center">
                            <i class="fas fa-bolt mr-2"></i>
                            Weekly AI-Powered Reports + breaking news digest
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Eve Section -->
    <section id="eve" class="py-20 bg-gradient-to-b from-cyber-gray via-cyber-gray to-black">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-2/5 flex justify-center mb-10 md:mb-0">
                    <div class="w-72 aspect-square bg-gradient-to-br from-purple-900 via-cyan-900 to-indigo-900 rounded-full flex items-center justify-center p-7 border-4 border-gray-700 relative">
                        <div class="absolute inset-0 animate-ping rounded-full bg-cyan-500 opacity-10"></div>
                        <div class="bg-gray-900 rounded-full w-full h-full flex items-center justify-center">
                            <div class="bg-gray-800 rounded-full w-48 h-48 flex items-center justify-center">
                                <div class="bg-gray-700 rounded-full w-36 h-36"></div>
                            </div>
                        </div>
                        <div class="absolute bottom-7 w-8 h-8 bg-cyber-cyan rounded-lg"></div>
                    </div>
                </div>
                <div class="md:w-3/5">
                    <h2 class="text-3xl md:text-4xl font-heading font-bold mb-6">
                        Meet Eve<span class="text-cyber-cyan">$</span>
                    </h2>
                    <p class="text-2xl mb-8 text-gray-300 leading-normal border-l-4 border-cyber-cyan pl-6 py-2">
                        "Your faceless research analyst. 24/7 alpha feed. No bias. No sleep."
                    </p>
                    <div class="space-y-4">
                        <div class="flex items-start">
                            <span class="mt-1 mr-3 block h-8 w-8 bg-purple-900 rounded-full flex items-center justify-center text-purple-300">
                                <i class="fas fa-gem"></i>
                            </span>
                            <p class="text-gray-400">AI assistant trained on 3M+ crypto data points, NLP analysis of Twitter, Telegram, and Discord.</p>
                        </div>
                        <div class="flex items-start">
                            <span class="mt-1 mr-3 block h-8 w-8 bg-cyan-900 rounded-full flex items-center justify-center text-cyan-300">
                                <i class="fas fa-robot"></i>
                            </span>
                            <p class="text-gray-400">Continuous analysis: CEX data, on-chain flows, liquidation levels, DEX volumes, governance proposals, and obscure CT alpha.</p>
                        </div>
                        <div class="flex items-start">
                            <span class="mt-1 mr-3 block h-8 w-8 bg-purple-900 rounded-full flex items-center justify-center text-purple-300">
                                <i class="fas fa-brain"></i>
                            </span>
                            <p class="text-gray-400">Surgical precision reports: technical/fundamental analysis without emotion, only data.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing -->
    <section id="pricing" class="py-20 bg-black">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-orbitron font-bold text-center mb-20">
                Ready<span class="text-cyber-cyan">?</span> Choose Your Plan
            </h2>
            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto">
                <!-- Starter Card -->
                <div class="border border-gray-800 rounded-xl bg-gradient-to-b from-cyber-gray via-gray-900 to-black py-8 px-6 flex flex-col">
                    <div class="mb-6">
                        <h3 class="font-heading font-bold text-2xl mb-3">Starter</h3>
                        <div class="text-2xl font-bold"><span class="text-cyber-cyan">$100</span>/report</div>
                        <div class="mt-4 text-sm text-gray-300 font-mono bg-cyber-purple bg-opacity-10 px-3 py-1 rounded inline-block">Pay-Per-Report</div>
                    </div>
                    <div class="flex-grow">
                        <ul class="space-y-4">
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Single Report Delivery</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>2 Asset Focus Areas</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Basic Analysis Metrics</span></li>
                            <li class="flex"><i class="fas fa-times text-red-400 mt-1 mr-3"></i><span>Alpha Feed Access</span></li>
                            <li class="flex"><i class="fas fa-times text-red-400 mt-1 mr-3"></i><span>AI Threads</span></li>
                        </ul>
                    </div>
                    <a href="#" class="mt-8 px-6 py-3 block text-center bg-gray-900 border border-gray-700 rounded-md hover:bg-gray-800">Get Alpha</a>
                </div>

                <!-- Pro Card -->
                <div class="border border-cyber-cyan rounded-xl bg-gradient-to-b from-cyan-900 via-cyber-gray to-black py-8 px-6 flex flex-col transform hover:scale-105 transition-transform">
                    <div class="mb-6">
                        <div class="flex justify-between">
                            <h3 class="font-heading font-bold text-2xl mb-3">Pro</h3>
                            <span class="font-mono text-xs bg-cyber-cyan text-cyber-dark px-2 py-1 rounded-md">Popular</span>
                        </div>
                        <div class="text-2xl font-bold"><span class="text-cyber-lime">$500</span>/month</div>
                        <div class="mt-4 text-sm text-gray-300 font-mono bg-cyber-green bg-opacity-50 px-3 py-1 rounded inline-block">Value Optimized</div>
                    </div>
                    <div class="flex-grow">
                        <ul class="space-y-4">
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Weekly AI-Powered Reports</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Multichain Analysis</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Crypto Twitter Alpha Feed</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Smart Money Wallet Tracking</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>2 Custom AI Requests/Month</span></li>
                        </ul>
                    </div>
                    <a href="#" class="mt-8 px-6 py-3 block text-center bg-cyber-cyan text-black font-bold rounded-md glow-box">Go Pro</a>
                </div>

                <!-- Enterprise Card -->
                <div class="border border-purple-500 rounded-xl bg-gradient-to-b from-purple-900 via-gray-900 to-black py-8 px-6 flex flex-col">
                    <div class="mb-6">
                        <h3 class="font-heading font-bold text-2xl mb-3">Custom</h3>
                        <div class="text-2xl font-bold"><span class="text-cyber-purple">Contact Us</span></div>
                        <div class="mt-4 text-sm text-gray-300 font-mono bg-cyber-purple bg-opacity-10 px-3 py-1 rounded inline-block">Enterprise Solution</div>
                    </div>
                    <div class="flex-grow">
                        <ul class="space-y-4">
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>VC/Fund Strategic Intelligence</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Portfolio Tracking Dashboard</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Whitelabel Reports</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>API Access w/ Custom Signals</span></li>
                            <li class="flex"><i class="fas fa-check text-green-400 mt-1 mr-3"></i><span>Dedicated Research Analyst</span></li>
                        </ul>
                    </div>
                    <a href="#" class="mt-8 px-6 py-3 block text-center bg-cyber-purple text-white rounded-md hover:bg-purple-500">Contact</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Sample Reports -->
    <section id="samples" class="py-20 bg-gradient-to-b from-cyber-gray to-cyber-dark">
        <div class="container mx-auto px-4">
            <h2 class="text-4xl font-heading font-bold text-center mb-16">
                Never Miss Alpha Again
            </h2>
            <div class="max-w-3xl mx-auto">
                <div class="dash bg-gray-900 border border-gray-800 rounded-xl p-8 relative">
                    <div class="absolute top-5 right-5 text-xs font-mono px-2 py-1 bg-cyan-800 rounded">Real Alpha</div>
                    <h3 class="text-xl font-orbitron mb-6 text-center">Sample Report: ETH Momentum Analysis</h3>
                    <div class="text-gray-300 font-mono space-y-4">
                        <div class="flex items-start">
                            <div class="mr-4 mt-1 text-cyber-purple">▶</div>
                            <div>
                                <div class="flex mb-1"><span class="block bg-purple-900 text-purple-300 px-2 rounded mr-2">TRIGGER</span> Whale accumulation detected through chain analysis</div>
                                <div class="text-cyan-300">4 addresses moved 18K+ ETH from exchanges in 48h period</div>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="mr-4 mt-1 text-cyber-red">▶</div>
                            <div>
                                <div class="flex mb-1"><span class="block bg-red-900 text-red-300 px-2 rounded mr-2">RISK</span> 1725 is key support - if broken expect cascade to 1665</div>
                                <div class="text-cyan-300">Liquidation cliffs at $1950 on major exchanges</div>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="mr-4 mt-1 text-cyber-green">▶</div>
                            <div>
                                <div class="flex mb-1"><span class="block bg-green-900 text-green-300 px-2 rounded mr-2">ALPHA</span> Staking inflows increasing pre-shanghai hardfork</div>
                                <div class="text-green-300">EIP-4844 proto-danksharding activation may induce new accumulation phase</div>
                            </div>
                        </div>
                        <div class="text-center mt-8 px-10 py-4 border border-cyber-purple rounded-lg">
                            <div class="text-xs uppercase tracking-wider mb-1">Eve's Analysis</div>
                            <div class="font-bold">Accumulate between $1600-$1750</div>
                        </div>
                        <div class="mt-8 text-center font-mono text-xs tracking-widest">
                            $ DeFi, Degen, Done Right $
                        </div>
                    </div>
                </div>
                <div class="mt-12 text-center">
                    <a href="#" class="border-2 border-cyber-purple font-orbitron px-8 py-4 inline-block rounded-md">
                        Download Full Report <i class="fas fa-arrow-down ml-2"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <div class="py-16 bg-gradient-to-r from-cyan-900 via-purple-900 to-black">
        <div class="container mx-auto px-4 text-center">
            <h3 class="text-3xl font-orbitron mb-6">Join the Alpha Frontline</h3>
            <p class="text-xl mb-10 max-w-2xl mx-auto">
                Your edge in the ever-evolving crypto markets is just one click away
            </p>
            <a href="#pricing" class="px-10 py-5 bg-gradient-to-r from-purple-600 to-cyan-500 font-bold text-xl inline-block hover:from-purple-500 hover:to-cyan-400 transition-all rounded-full">
                Get Started <i class="fas fa-arrow-right ml-2"></i>
            </a>
        </div>
    </div>

    <!-- Footer -->
    <footer class="bg-black border-t border-gray-800 py-12">
        <div class="container mx-auto px-4">
            <div class="flex flex-col md:flex-row justify-between items-center">
                <div class="mb-8 md:mb-0">
                    <div class="font-heading font-bold text-2xl mb-2">Crypto Alpha AI</div>
                    <div class="text-sm max-w-xs text-gray-500">
                        Precision crypto reports for traders, founders, and VCs.
                    </div>
                </div>
                <div class="flex space-x-8">
                    <a href="#" class="hover:text-cyber-cyan"><i class="fab fa-twitter"></i></a>
                    <a href="#" class="hover:text-cyber-cyan"><i class="fab fa-telegram"></i></a>
                    <a href="#" class="hover:text-cyber-cyan"><i class="fab fa-discord"></i></a>
                    <a href="#" class="hover:text-cyber-cyan"><i class="fab fa-github"></i></a>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-500 text-sm font-mono">
                $ ETH: 0x1a2b...3c4d $ • Alpha since 2021
            </div>
        </div>
    </footer>

    <!-- Script -->
    <script>
        // Header scroll effect
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 100) {
                header.classList.add('shadow-lg')
            } else {
                header.classList.remove('shadow-lg')
            }
        })
        
        // Pricing hover effect for enterprise card
        const enterpriseCard = document.querySelector('#pricing > div > div:nth-child(3)')
        enterpriseCard.addEventListener('mouseenter', () => {
            enterpriseCard.classList.add('scale-[1.02]')
            enterpriseCard.classList.add('border-cyber-purple')
        })
        enterpriseCard.addEventListener('mouseleave', () => {
            enterpriseCard.classList.remove('scale-[1.02]')
            enterpriseCard.classList.remove('border-cyber-purple')
        })
    </script>
</body>
</html>
