<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            background: radial-gradient(circle at center, #2d0505 0%, #000000 100%);
            font-family: 'Inter', sans-serif;
            color: white;
            min-height: 100vh;
        }
        .futuristic-font { font-family: 'Orbitron', sans-serif; }
        .glass-card {
            background: rgba(255, 255, 255, 0.03);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(220, 38, 38, 0.2);
            box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.8);
        }
        .hero-glow {
            filter: drop-shadow(0 0 35px rgba(220, 38, 38, 0.6));
        }
        .red-spotlight {
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 400px;
            height: 400px;
            background: rgba(220, 38, 38, 0.15);
            filter: blur(100px);
            border-radius: 50%;
            z-index: -1;
        }
    </style>
</head>
<body class="p-8">

    <nav class="flex justify-between items-center mb-16">
        <h1 class="futuristic-font text-2xl font-bold tracking-widest text-red-600">AURORA</h1>
        <div class="space-x-8 text-sm uppercase tracking-wider">
            <a href="#" class="hover:text-red-500 transition">Products</a>
            <a href="#" class="hover:text-red-500 transition">Innovation</a>
            <a href="#" class="hover:text-red-500 transition">Support</a>
        </div>
        <div class="glass-card px-4 py-2 rounded-full cursor-pointer">
            <span>Cart (0)</span>
        </div>
    </nav>

    <main class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12 items-center relative">
        <div class="red-spotlight"></div>
        
        <div class="space-y-6">
            <span class="text-red-500 font-semibold tracking-widest uppercase text-xs">Premium Audio Series</span>
            <h2 class="futuristic-font text-6xl font-black leading-tight">AETHER <br><span class="text-red-600">FLOW-X</span></h2>
            <p class="text-gray-400 text-lg max-w-md">Experience cinematic sound with hybrid active noise cancellation and 60-hour battery life.</p>
            
            <div class="flex gap-4 pt-4">
                <button class="bg-red-600 hover:bg-red-700 text-white px-8 py-4 rounded-sm futuristic-font transition-all transform hover:scale-105">
                    BUY NOW - $299
                </button>
                <button class="glass-card px-8 py-4 rounded-sm hover:bg-white/5 transition">
                    DETAILS
                </button>
            </div>
        </div>

        <div class="relative flex justify-center">
            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&q=80&w=1000" 
                 alt="Headphones" 
                 class="hero-glow w-full max-w-md mix-blend-lighten">
        </div>
    </main>

    <section class="mt-24 grid grid-cols-1 md:grid-cols-3 gap-6">
        <div class="glass-card p-6 rounded-xl">
            <h3 class="futuristic-font text-red-500 mb-2">Noise Cancellation</h3>
            <p class="text-sm text-gray-400">Industry leading -40dB isolation for pure focus.</p>
        </div>
        <div class="glass-card p-6 rounded-xl border-red-600/50">
            <h3 class="futuristic-font text-red-500 mb-2">Battery Life</h3>
            <p class="text-sm text-gray-400">Up to 60
