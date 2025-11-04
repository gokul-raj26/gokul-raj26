<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gokul Raj M - Developer Infographic</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.9.1/chart.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700;800&display=swap" rel="stylesheet">
    <style>
      body {
        font-family: 'Inter', sans-serif;
      }
      .chart-container {
        position: relative;
        width: 100%;
        max-width: 500px;
        margin-left: auto;
        margin-right: auto;
        height: 350px;
        max-height: 400px;
      }
      @media (min-width: 768px) {
        .chart-container {
          height: 400px;
          max-height: 450px;
        }
      }
    </style>
</head>
<body class="bg-slate-100 text-slate-800">

    <main class="container mx-auto p-4 md:p-8 max-w-6xl">

        <header class="text-center p-10 md:p-16 bg-white rounded-lg shadow-md mb-8 border-b-4 border-[#005BC6]">
            <h1 class="text-4xl md:text-5xl font-extrabold text-[#00449E]">Hi, I'm Gokul Raj M</h1>
            <h2 class="text-xl md:text-3xl text-slate-700 mt-3">A Passionate Full-Stack & .NET Developer 🚀</h2>
            <p class="text-lg text-slate-600 mt-4 max-w-2xl mx-auto">Focused on building scalable enterprise applications using the Microsoft stack and modern React frontends.</p>
        </header>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">

            <section class="bg-white rounded-lg shadow-md p-6">
                <h3 class="text-2xl font-bold text-[#00449E] mb-4">Core Expertise</h3>
                <p class="text-slate-600 mb-6">This radar chart visualizes my primary areas of expertise. These are the technologies I work with daily and am comfortable discussing in depth, from architectural decisions to hands-on implementation.</p>
                <div class="chart-container">
                    <canvas id="skillsRadarChart"></canvas>
                </div>
                <p class="text-slate-500 text-sm mt-4 text-center">A visualization of confidence and experience across my key skillsets.</p>
            </section>

            <section class="bg-white rounded-lg shadow-md p-6">
                <h3 class="text-2xl font-bold text-[#00449E] mb-4">Technology Stack Composition</h3>
                <p class="text-slate-600 mb-6">My toolkit is broad and balanced. This chart breaks down the technologies I use by their primary domain, showing a strong focus on both backend architecture and modern frontend development.</p>
                <div class="chart-container">
                    <canvas id="stackDonutChart"></canvas>
                </div>
                <p class="text-slate-500 text-sm mt-4 text-center">A proportional breakdown of my technical skills by category.</p>
            </section>

            <section class="lg:col-span-2 bg-white rounded-lg shadow-md p-6">
                <h3 class="text-2xl font-bold text-[#00449E] mb-4">Current Focus & Growth Path</h3>
                
                <h4 class="text-xl font-semibold text-slate-700 mb-2">🔭 Current Project</h4>
                <div class="bg-slate-50 rounded-lg p-5 border-l-4 border-[#005BC6]">
                    <h5 class="text-lg font-bold text-[#005BC6]">Haweye – Management Console Dashboard</h5>
                    <p class="text-slate-600 mt-1">I am currently contributing to this robust web-based admin console built with <strong>React</strong> and <strong>ASP.NET Core API</strong> for comprehensive project, timesheet, and performance analytics.</p>
                </div>

                <h4 class="text-xl font-semibold text-slate-700 mt-8 mb-4">🌱 My Learning & Growth Path</h4>
                <p class="text-slate-600 mb-6">Technology is always evolving, and so am I. This path shows how I'm building on my current stack to integrate next-generation technologies into my skillset.</p>
                
                <div class="flex flex-col md:flex-row items-center justify-between mt-4 text-center gap-4">
                    
                    <div class="w-full md:w-1/3 bg-white p-4 rounded-lg shadow border border-slate-200">
                        <h6 class="font-bold text-[#00449E]">Current Stack</h6>
                        <p class="text-slate-600 text-sm">.NET Core & React</p>
                    </div>

                    <span class="text-4xl text-[#0077F0] font-bold mx-4 rotate-90 md:rotate-0" aria-hidden="true">&rarr;</span>

                    <div class="w-full md:w-1/3 bg-blue-50 p-4 rounded-lg shadow border border-[#529CF3]">
                        <h6 class="font-bold text-[#005BC6]">Actively Learning</h6>
                        <p class="text-slate-600 text-sm">.NET+AI, Snowflake, React Native</p>
                    </div>

                    <span class="text-4xl text-[#0077F0] font-bold mx-4 rotate-90 md:rotate-0" aria-hidden="true">&rarr;</span>

                    <div class="w-full md:w-1/3 bg-white p-4 rounded-lg shadow border border-slate-200">
                        <h6 class="font-bold text-[#00449E]">Future Focus</h6>
                        <p class="text-slate-600 text-sm">AI-Driven Apps & Data Solutions</p>
                    </div>
                </div>
            </section>

        </div>

        <footer class="mt-8 grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
            <a href="https://linkedin.com/in/gokulraj-gimzr" target="_blank" rel="noopener" class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col items-center justify-center">
                <span class="text-3xl mb-2" aria-hidden="true">🔗</span>
                <h4 class="text-xl font-bold text-[#005BC6]">Connect on LinkedIn</h4>
                <p class="text-slate-500">linkedin.com/in/gokulraj-gimzr</p>
            </a>
            
            <a href="mailto:gokulrajm.dev@gmail.com" class="bg-white rounded-lg shadow-md p-6 hover:shadow-xl transition-shadow duration-300 flex flex-col items-center justify-center">
                 <span class="text-3xl mb-2" aria-hidden="true">📧</span>
                <h4 class="text-xl font-bold text-[#005BC6]">Reach Me Via Email</h4>
                <p class="text-slate-500">gokulrajm.dev@gmail.com</p>
            </a>

            <div class="bg-white rounded-lg shadow-md p-6 flex flex-col items-center justify-center">
                 <span class="text-3xl mb-2" aria-hidden="true">⚡</span>
                <h4 class="text-xl font-bold text-[#005BC6]">Fun Fact</h4>
                <p class="text-slate-500">I debug better with lo-fi music 🎧 and coffee ☕ in hand.</p>
            </div>
        </footer>
    </main>

    <script>
        (function() {
            
            const tooltipTitleCallback = (tooltipItems) => {
              const item = tooltipItems[0];
              let label = item.chart.data.labels[item.dataIndex];
              if (Array.isArray(label)) {
                return label.join(' ');
              } else {
                return label;
              }
            };

            const commonTooltipOptions = {
                plugins: {
                    tooltip: {
                        callbacks: {
                            title: tooltipTitleCallback
                        },
                        backgroundColor: '#FFFFFF',
                        titleColor: '#00449E',
                        bodyColor: '#334155',
                        borderColor: '#9BC7F9',
                        borderWidth: 1,
                        padding: 10,
                        displayColors: false
                    }
                }
            };
            
            const radarLabels = ['C#', 'ASP.NET Core', 'SQL Server', 'React', 'TypeScript', 'REST APIs', ['Building', 'Real-World', 'Dashboards'], 'GSAP'];
            const radarData = {
              labels: radarLabels,
              datasets: [{
                label: 'Expertise Level',
                data: [9, 9, 8, 8, 8, 9, 7, 6],
                backgroundColor: 'rgba(0, 119, 240, 0.2)',
                borderColor: '#0077F0',
                pointBackgroundColor: '#0077F0',
                pointBorderColor: '#fff',
                pointHoverBackgroundColor: '#fff',
                pointHoverBorderColor: '#0077F0'
              }]
            };

            const radarConfig = {
              type: 'radar',
              data: radarData,
              options: {
                maintainAspectRatio: false,
                plugins: commonTooltipOptions.plugins,
                scales: {
                  r: {
                    angleLines: { color: '#cbd5e1' },
                    grid: { color: '#e2e8f0' },
                    pointLabels: {
                      color: '#00449E',
                      font: {
                        size: 12,
                        weight: '600'
                      }
                    },
                    ticks: {
                      backdropColor: 'transparent',
                      color: '#64748b',
                      stepSize: 2,
                      display: false
                    },
                    suggestedMin: 0,
                    suggestedMax: 10
                  }
                },
                elements: {
                  line: {
                    borderWidth: 3
                  }
                }
              }
            };

            const ctxRadar = document.getElementById('skillsRadarChart');
            if(ctxRadar) {
                new Chart(ctxRadar.getContext('2d'), radarConfig);
            }

            const donutLabels = [['Backend &', 'Database'], ['Frontend &', 'UI/UX'], ['Mobile', 'Development'], ['DevOps &', 'Tooling']];
            const donutData = {
                labels: donutLabels,
                datasets: [{
                    label: 'Technology Stack',
                    data: [8, 6, 3, 3],
                    backgroundColor: [
                        '#00449E',
                        '#005BC6',
                        '#0077F0',
                        '#529CF3'
                    ],
                    borderColor: '#FFFFFF',
                    borderWidth: 3,
                    hoverOffset: 4
                }]
            };

            const donutConfig = {
                type: 'doughnut',
                data: donutData,
                options: {
                    maintainAspectRatio: false,
                    responsive: true,
                    plugins: {
                        ...commonTooltipOptions.plugins,
                        legend: {
                            position: 'bottom',
                            labels: {
                                color: '#334155',
                                font: {
                                    size: 12
                                },
                                usePointStyle: true
                            }
                        }
                    },
                    cutout: '60%'
                }
            };

            const ctxDonut = document.getElementById('stackDonutChart');
            if(ctxDonut) {
                new Chart(ctxDonut.getContext('2d'), donutConfig);
            }

        })();
    </script>
</body>
</html>
