<!DOCTYPE html>

<html lang="en"><head>
<meta charset="utf-8"/>
<meta content="width=device-width, initial-scale=1.0" name="viewport"/>
<title>Waste OS - Community Reports</title>
<script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&amp;family=Space+Grotesk:wght@500;600&amp;family=JetBrains+Mono:wght@400;500&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<link href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&amp;display=swap" rel="stylesheet"/>
<script id="tailwind-config">
        tailwind.config = {
            darkMode: "class",
            theme: {
                extend: {
                    "colors": {
                        "surface-container-highest": "#dee3e9",
                        "tertiary": "#8a5100",
                        "surface-container": "#eaeef4",
                        "on-tertiary-fixed-variant": "#693c00",
                        "secondary": "#505f76",
                        "on-primary-fixed": "#001e2f",
                        "on-tertiary-container": "#4d2b00",
                        "on-surface": "#171c20",
                        "inverse-primary": "#89ceff",
                        "primary-fixed-dim": "#89ceff",
                        "on-tertiary": "#ffffff",
                        "on-primary-fixed-variant": "#004c6e",
                        "secondary-fixed-dim": "#b7c8e1",
                        "surface": "#f6faff",
                        "secondary-container": "#d0e1fb",
                        "on-secondary-container": "#54647a",
                        "background": "#f6faff",
                        "on-error-container": "#93000a",
                        "error-container": "#ffdad6",
                        "surface-dim": "#d6dae0",
                        "outline": "#6e7881",
                        "tertiary-fixed-dim": "#ffb86e",
                        "tertiary-fixed": "#ffdcbd",
                        "surface-container-high": "#e4e8ee",
                        "tertiary-container": "#de8712",
                        "surface-tint": "#006591",
                        "on-surface-variant": "#3e4850",
                        "on-primary": "#ffffff",
                        "primary": "#006591",
                        "error": "#ba1a1a",
                        "on-background": "#171c20",
                        "on-secondary-fixed-variant": "#38485d",
                        "surface-variant": "#dee3e9",
                        "surface-bright": "#f6faff",
                        "on-secondary": "#ffffff",
                        "on-primary-container": "#003751",
                        "inverse-on-surface": "#edf1f7",
                        "primary-fixed": "#c9e6ff",
                        "inverse-surface": "#2c3135",
                        "on-secondary-fixed": "#0b1c30",
                        "secondary-fixed": "#d3e4fe",
                        "surface-container-low": "#f0f4fa",
                        "primary-container": "#0ea5e9",
                        "outline-variant": "#bec8d2",
                        "on-error": "#ffffff",
                        "surface-container-lowest": "#ffffff",
                        "on-tertiary-fixed": "#2c1600"
                    },
                    "borderRadius": {
                        "DEFAULT": "0.25rem",
                        "lg": "0.5rem",
                        "xl": "0.75rem",
                        "full": "9999px"
                    },
                    "spacing": {
                        "xs": "4px",
                        "sm": "8px",
                        "unit": "4px",
                        "xl": "48px",
                        "md": "16px",
                        "lg": "24px",
                        "gutter": "20px",
                        "container-margin": "32px"
                    },
                    "fontFamily": {
                        "display-lg": ["Space Grotesk"],
                        "body-base": ["Inter"],
                        "label-caps": ["Inter"],
                        "headline-md": ["Space Grotesk"],
                        "body-sm": ["Inter"],
                        "data-point": ["JetBrains Mono"],
                        "data-lg": ["JetBrains Mono"]
                    },
                    "fontSize": {
                        "display-lg": ["36px", { "lineHeight": "1.2", "letterSpacing": "-0.02em", "fontWeight": "600" }],
                        "body-base": ["16px", { "lineHeight": "1.5", "fontWeight": "400" }],
                        "label-caps": ["12px", { "lineHeight": "1", "letterSpacing": "0.05em", "fontWeight": "600" }],
                        "headline-md": ["24px", { "lineHeight": "1.3", "fontWeight": "500" }],
                        "body-sm": ["14px", { "lineHeight": "1.4", "fontWeight": "400" }],
                        "data-point": ["15px", { "lineHeight": "1", "fontWeight": "500" }],
                        "data-lg": ["28px", { "lineHeight": "1", "fontWeight": "400" }]
                    }
                }
            }
        }
    </script>
<style>
        body {
            background-color: #f6faff;
        }
    </style>
</head>
<body class="bg-background text-on-background font-body-base antialiased selection:bg-primary-container selection:text-on-primary-container">
<!-- Side NavBar (Desktop Only) -->
<nav class="hidden md:flex flex-col gap-md p-md bg-surface border-r border-outline-variant fixed h-full w-64 left-0 top-0 z-40">
<div class="flex items-center gap-sm px-sm py-lg">
<span class="material-symbols-outlined text-primary text-3xl" style="font-variation-settings: 'FILL' 1;">eco</span>
<div>
<h1 class="font-display-lg text-display-lg text-primary font-bold leading-none">Waste OS</h1>
<p class="font-label-caps text-label-caps text-on-surface-variant mt-xs">IoT Logistics</p>
</div>
</div>
<div class="flex flex-col gap-sm mt-md flex-grow">
<!-- Inactive Tab -->
<a class="flex items-center gap-md px-md py-sm rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors cursor-pointer active:scale-95" href="#">
<span class="material-symbols-outlined">sensors</span>
<span class="font-body-base text-body-base">Live Monitor</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-md px-md py-sm rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors cursor-pointer active:scale-95" href="#">
<span class="material-symbols-outlined">analytics</span>
<span class="font-body-base text-body-base">Analytics</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-md px-md py-sm rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors cursor-pointer active:scale-95" href="#">
<span class="material-symbols-outlined">delete</span>
<span class="font-body-base text-body-base">Bin Management</span>
</a>
<!-- Active Tab -->
<a class="flex items-center gap-md px-md py-sm rounded-lg text-primary font-bold border-r-2 border-primary bg-surface-container-low cursor-pointer active:scale-95" href="#">
<span class="material-symbols-outlined" style="font-variation-settings: 'FILL' 1;">report</span>
<span class="font-body-base text-body-base">Community Reports</span>
</a>
<!-- Inactive Tab -->
<a class="flex items-center gap-md px-md py-sm rounded-lg text-on-surface-variant hover:bg-surface-container-low transition-colors cursor-pointer active:scale-95 mt-auto" href="#">
<span class="material-symbols-outlined">settings</span>
<span class="font-body-base text-body-base">System Settings</span>
</a>
</div>
<div class="flex items-center gap-md p-sm mt-sm border-t border-outline-variant pt-md">
<img alt="User avatar" class="w-10 h-10 rounded-full object-cover" data-alt="A small circular profile picture of a professional individual, well-lit against a neutral background, suitable for a modern tech dashboard avatar." src="https://lh3.googleusercontent.com/aida-public/AB6AXuBZwP5Lwbu3INm182gegkjd0u1QCRUerzu6NCQgtledlu5vPW1GmAHKG_JNRvXRGKD15np7AUHhoTav4B9MPcqU4HuNDMq1Px-Dj37F7C9cSWZjVpAf2tdsWYx298G5-rDO9nwLFoGlPDB-qMTbrBhkKprzoSFicO0w-aiMwjvN9nNSvTUxzi9JE_EoNggHt-UZ4izxb6woIIi6RrOWmxsOHcyKo9adyGp4vOgjLLMTlYGSr1gn06kXk1wAqZnrsDzPU6IpFQUmaq_w"/>
<div class="flex flex-col">
<span class="font-body-sm text-body-sm font-medium">Admin User</span>
<span class="font-label-caps text-label-caps text-on-surface-variant">Logistics</span>
</div>
</div>
</nav>
<!-- Main Content Wrapper -->
<div class="md:ml-64 min-h-screen flex flex-col">
<!-- Top App Bar (Desktop Only) -->
<header class="hidden md:flex justify-between items-center h-16 px-lg bg-surface border-b border-outline-variant sticky top-0 z-30">
<div class="flex-1">
<!-- Left Search placeholder if needed, empty per design -->
</div>
<div class="flex items-center gap-md">
<button class="p-sm rounded-full text-on-surface-variant hover:bg-surface-container-high transition-all cursor-pointer active:opacity-80">
<span class="material-symbols-outlined">notifications</span>
</button>
</div>
</header>
<!-- Main Canvas -->
<main class="flex-1 p-md md:p-container-margin overflow-y-auto">
<div class="max-w-6xl mx-auto">
<div class="flex flex-col md:flex-row justify-between items-start md:items-end mb-xl gap-md">
<div>
<h2 class="font-headline-md text-headline-md text-on-surface mb-xs">Community Reports</h2>
<p class="font-body-sm text-body-sm text-on-surface-variant">Review and manage issue submissions from public citizens and field operators.</p>
</div>
<div class="flex gap-sm">
<button class="px-md py-sm bg-surface rounded-lg border border-outline-variant text-on-surface font-body-sm text-body-sm hover:bg-surface-container-low transition-colors shadow-[0px_4px_12px_rgba(30,41,59,0.05)] flex items-center gap-sm">
<span class="material-symbols-outlined text-[18px]">filter_list</span>
                            Filter
                        </button>
</div>
</div>
<div class="grid grid-cols-1 lg:grid-cols-12 gap-lg">
<!-- Left Column: Submit a Report Form (Bento/Card) -->
<div class="lg:col-span-4 flex flex-col gap-lg">
<div class="bg-surface rounded-[16px] border border-outline-variant p-lg shadow-[0px_4px_12px_rgba(30,41,59,0.05)]">
<h3 class="font-headline-md text-headline-md text-on-surface mb-md">Submit a Report</h3>
<form class="flex flex-col gap-md">
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-xs">Issue Type</label>
<select class="w-full bg-surface border border-outline-variant rounded-lg p-sm font-body-sm text-body-sm text-on-surface focus:ring-2 focus:ring-primary-container focus:border-transparent outline-none">
<option>Overflowing Container</option>
<option>Hardware Damage</option>
<option>Illegal Dumping</option>
<option>Other</option>
</select>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-xs">Location (Bin ID or Address)</label>
<div class="relative">
<span class="material-symbols-outlined absolute left-sm top-1/2 -translate-y-1/2 text-outline text-[18px]">location_on</span>
<input class="w-full bg-surface border border-outline-variant rounded-lg py-sm pl-xl pr-sm font-body-sm text-body-sm text-on-surface placeholder:text-outline focus:ring-2 focus:ring-primary-container focus:border-transparent outline-none" placeholder="e.g. BIN-492 or 123 Main St" type="text"/>
</div>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-xs">Photo Evidence</label>
<div class="border-2 border-dashed border-outline-variant rounded-lg p-md text-center bg-surface-container-lowest hover:bg-surface-container-low transition-colors cursor-pointer group">
<span class="material-symbols-outlined text-outline group-hover:text-primary transition-colors text-[32px] mb-xs">add_a_photo</span>
<p class="font-body-sm text-body-sm text-on-surface-variant group-hover:text-primary">Click or drag to upload</p>
</div>
</div>
<div>
<label class="block font-label-caps text-label-caps text-on-surface-variant mb-xs">Description</label>
<textarea class="w-full bg-surface border border-outline-variant rounded-lg p-sm font-body-sm text-body-sm text-on-surface placeholder:text-outline focus:ring-2 focus:ring-primary-container focus:border-transparent outline-none resize-none" placeholder="Additional details..." rows="3"></textarea>
</div>
<button class="mt-sm w-full bg-[#0EA5E9] text-white font-body-base text-body-base py-sm rounded-lg hover:bg-primary transition-colors focus:ring-2 focus:ring-offset-2 focus:ring-[#0EA5E9] outline-none" type="button">
                                    Submit Report
                                </button>
</form>
</div>
<!-- Quick Stats Mini Card -->
<div class="bg-primary-container rounded-[16px] p-lg shadow-[0px_4px_12px_rgba(30,41,59,0.05)] text-on-primary">
<div class="flex items-center justify-between mb-sm">
<span class="font-label-caps text-label-caps opacity-80">Community Engagement</span>
<span class="material-symbols-outlined">forum</span>
</div>
<div class="font-data-lg text-data-lg mb-xs">142</div>
<div class="font-body-sm text-body-sm opacity-90">Reports resolved this week</div>
</div>
</div>
<!-- Right Column: Recent Feed -->
<div class="lg:col-span-8 flex flex-col gap-md">
<div class="flex justify-between items-center px-sm">
<h3 class="font-body-base text-body-base font-medium text-on-surface">Recent Feed</h3>
<span class="font-label-caps text-label-caps text-on-surface-variant">Live Updates</span>
</div>
<!-- Feed Item 1 -->
<div class="bg-surface rounded-[16px] border border-outline-variant p-md shadow-[0px_4px_12px_rgba(30,41,59,0.05)] hover:border-primary-container transition-colors cursor-pointer group">
<div class="flex items-start gap-md">
<div class="w-12 h-12 rounded-lg bg-error-container text-on-error-container flex items-center justify-center flex-shrink-0">
<span class="material-symbols-outlined">delete_sweep</span>
</div>
<div class="flex-1">
<div class="flex justify-between items-start mb-xs">
<h4 class="font-body-base text-body-base font-medium text-on-surface">Overflowing Container</h4>
<span class="inline-flex items-center px-2 py-1 rounded-full bg-surface-container-high text-on-surface-variant font-label-caps text-[10px]">Pending</span>
</div>
<div class="flex items-center gap-xs font-body-sm text-body-sm text-on-surface-variant mb-sm">
<span class="material-symbols-outlined text-[16px]">location_on</span>
<span>BIN-882 • North Park Sector</span>
<span class="mx-sm opacity-50">•</span>
<span>10 mins ago</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface mb-md">Sensor reads normal but citizen report shows debris surrounding the base of the container. Requires manual cleanup.</p>
<div class="flex gap-sm">
<img alt="Trash around bin" class="w-24 h-16 rounded object-cover border border-outline-variant" data-alt="A close-up shot of an overflowing modern metal public trash bin in a city park setting. Bright daylight illuminates the scattered debris around the base, highlighting the contrast between the clean park path and the messy container area. Modern IoT waste management context." src="https://lh3.googleusercontent.com/aida-public/AB6AXuCOh_Jx4kwkq5jCOckrMABkpYF6CY5fs1yJWfzd0Iq5tLT-hY7oMhBK2M-vLDyUQZp9hnXJN2aFntTKY8PaRT0fvLtAhaT6l8DsbH2gtL5RBmHz_P9ZzgIiGOBXOyXV1hFkew51AjmeIa0Qat2yez_X9b4zqzue0rgiC-hA-Ko2d2hnGjUtuaOsgbOF8jSHq2s139BW6r7GV12QIPpXOqU2paE2DK9-TJCrn3_YL6WY_UmmZDDiwxPJN7Rl3jb_mATZqUJMZUrE32pa"/>
</div>
</div>
</div>
<div class="mt-md pt-md border-t border-outline-variant flex justify-end gap-sm opacity-0 group-hover:opacity-100 transition-opacity">
<button class="px-sm py-xs bg-[#F1F5F9] text-[#1E293B] rounded font-label-caps text-label-caps hover:bg-surface-container-high transition-colors">Assign Crew</button>
<button class="px-sm py-xs bg-[#0EA5E9] text-white rounded font-label-caps text-label-caps hover:bg-primary transition-colors">Mark Resolved</button>
</div>
</div>
<!-- Feed Item 2 -->
<div class="bg-surface rounded-[16px] border border-outline-variant p-md shadow-[0px_4px_12px_rgba(30,41,59,0.05)] hover:border-primary-container transition-colors cursor-pointer group">
<div class="flex items-start gap-md">
<div class="w-12 h-12 rounded-lg bg-tertiary-container text-on-tertiary-container flex items-center justify-center flex-shrink-0">
<span class="material-symbols-outlined">build</span>
</div>
<div class="flex-1">
<div class="flex justify-between items-start mb-xs">
<h4 class="font-body-base text-body-base font-medium text-on-surface">Hardware Damage</h4>
<span class="inline-flex items-center px-2 py-1 rounded-full bg-secondary-container text-on-secondary-container font-label-caps text-[10px]">In Progress</span>
</div>
<div class="flex items-center gap-xs font-body-sm text-body-sm text-on-surface-variant mb-sm">
<span class="material-symbols-outlined text-[16px]">location_on</span>
<span>BIN-401 • Downtown Transit Station</span>
<span class="mx-sm opacity-50">•</span>
<span>2 hours ago</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface">Solar panel enclosure appears cracked. Sensor is still transmitting but power levels are dropping.</p>
</div>
</div>
<div class="mt-md pt-md border-t border-outline-variant flex justify-end gap-sm opacity-0 group-hover:opacity-100 transition-opacity">
<button class="px-sm py-xs bg-[#F1F5F9] text-[#1E293B] rounded font-label-caps text-label-caps hover:bg-surface-container-high transition-colors">Update Status</button>
</div>
</div>
<!-- Feed Item 3 -->
<div class="bg-surface rounded-[16px] border border-outline-variant p-md shadow-[0px_4px_12px_rgba(30,41,59,0.05)] hover:border-primary-container transition-colors cursor-pointer opacity-70 group">
<div class="flex items-start gap-md">
<div class="w-12 h-12 rounded-lg bg-surface-container-high text-on-surface-variant flex items-center justify-center flex-shrink-0">
<span class="material-symbols-outlined">check_circle</span>
</div>
<div class="flex-1">
<div class="flex justify-between items-start mb-xs">
<h4 class="font-body-base text-body-base font-medium text-on-surface line-through">Illegal Dumping</h4>
<span class="inline-flex items-center px-2 py-1 rounded-full bg-surface-container-low text-on-surface-variant font-label-caps text-[10px] border border-outline-variant">Resolved</span>
</div>
<div class="flex items-center gap-xs font-body-sm text-body-sm text-on-surface-variant mb-sm">
<span class="material-symbols-outlined text-[16px]">location_on</span>
<span>Alley behind 5th Ave</span>
<span class="mx-sm opacity-50">•</span>
<span>Yesterday</span>
</div>
<p class="font-body-sm text-body-sm text-on-surface-variant">Large furniture items left next to recycling bins. Cleared by Team Alpha.</p>
</div>
</div>
</div>
</div>
</div>
</div>
</main>
</div>
</body></html>