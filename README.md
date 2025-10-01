<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Storyteller Project Analysis</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700;800&display=swap" rel="stylesheet">
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
            height: 300px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
    </style>
</head>
<body class="bg-[#F0F8FF]">

    <div class="container mx-auto p-4 md:p-8">

        <header class="text-center my-12">
            <h1 class="text-4xl md:text-6xl font-extrabold text-[#004AAD]">Deconstructing the AI Storyteller</h1>
            <p class="text-lg md:text-xl text-[#3D3D3D] mt-4 max-w-3xl mx-auto">An infographic breakdown of a multi-modal AI application, from core features and technology stack to its impressive development journey.</p>
        </header>

        <main class="space-y-16">

            <section id="features">
                <h2 class="text-3xl font-bold text-center text-[#004AAD] mb-8">Core Project Features</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="bg-white rounded-lg shadow-md p-6 text-center hover:shadow-xl transition-shadow duration-300">
                        <div class="text-6xl mb-4">📖</div>
                        <h3 class="text-xl font-bold text-[#004AAD]">AI Story Generation</h3>
                        <p class="text-[#3D3D3D] mt-2">Leverages Natural Language Processing to generate creative stories from text and image prompts.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 text-center hover:shadow-xl transition-shadow duration-300">
                        <div class="text-6xl mb-4">🗣️</div>
                        <h3 class="text-xl font-bold text-[#004AAD]">Text-to-Speech (TTS)</h3>
                        <p class="text-[#3D3D3D] mt-2">Converts generated text into audible stories with multiple voice and accent options.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 text-center hover:shadow-xl transition-shadow duration-300">
                        <div class="text-6xl mb-4">🎨</div>
                        <h3 class="text-xl font-bold text-[#004AAD]">Story Customization</h3>
                        <p class="text-[#3D3D3D] mt-2">Users can tailor stories by defining parameters like tone and length for unique outputs.</p>
                    </div>
                    <div class="bg-white rounded-lg shadow-md p-6 text-center hover:shadow-xl transition-shadow duration-300">
                        <div class="text-6xl mb-4">📦</div>
                        <h3 class="text-xl font-bold text-[#004AAD]">Multiple Export Options</h3>
                        <p class="text-[#3D3D3D] mt-2">Provides the final story as a downloadable PDF document and an MP3 audio file.</p>
                    </div>
                </div>
            </section>

            <section id="tech-stack" class="bg-white rounded-lg shadow-md p-6 md:p-8">
                <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                    <div>
                        <h2 class="text-3xl font-bold text-[#004AAD] mb-4">The Technology Stack</h2>
                        <p class="text-[#3D3D3D]">The project is built on a foundation of powerful, modern libraries, each playing a critical role. The chart illustrates the key components that power the AI Storyteller, from core AI models for generation and captioning to the frameworks that deliver the user interface and final outputs.</p>
                    </div>
                    <div class="chart-container">
                        <canvas id="techStackChart"></canvas>
                    </div>
                </div>
            </section>
            
            <section id="journey">
                <h2 class="text-3xl font-bold text-center text-[#004AAD] mb-12">The 5-Day Development Journey</h2>
                <div class="relative flex flex-col items-center">
                     <div class="absolute left-1/2 top-0 bottom-0 w-1 bg-[#B4E2FF] -translate-x-1/2"></div>
                     <div class="w-full p-4">
                        <div class="relative md:flex md:items-center mb-12">
                            <div class="md:w-1/2 text-center md:text-right md:pr-8 z-10">
                                <div class="p-6 bg-white rounded-lg shadow-md">
                                    <p class="text-sm text-[#0094FF] font-semibold">DAY 1</p>
                                    <h3 class="text-xl font-bold text-[#004AAD]">Text-Based Generation</h3>
                                    <p class="text-[#3D3D3D]">Established the core functionality using the Gemini API to generate stories from user text prompts.</p>
                                </div>
                            </div>
                             <div class="absolute left-1/2 -translate-x-1/2 w-8 h-8 bg-[#0094FF] rounded-full border-4 border-white z-20 hidden md:block"></div>
                            <div class="md:w-1/2"></div>
                        </div>
                        <div class="relative md:flex md:flex-row-reverse md:items-center mb-12">
                            <div class="md:w-1/2 text-center md:text-left md:pl-8 z-10">
                                <div class="p-6 bg-white rounded-lg shadow-md">
                                    <p class="text-sm text-[#0094FF] font-semibold">DAY 2</p>
                                    <h3 class="text-xl font-bold text-[#004AAD]">Image-to-Story</h3>
                                    <p class="text-[#3D3D3D]">Integrated the BLIP model to generate descriptive captions from images, turning visual input into story prompts.</p>
                                </div>
                            </div>
                             <div class="absolute left-1/2 -translate-x-1/2 w-8 h-8 bg-[#0094FF] rounded-full border-4 border-white z-20 hidden md:block"></div>
                            <div class="md:w-1/2"></div>
                        </div>
                        <div class="relative md:flex md:items-center mb-12">
                            <div class="md:w-1/2 text-center md:text-right md:pr-8 z-10">
                               <div class="p-6 bg-white rounded-lg shadow-md">
                                    <p class="text-sm text-[#0094FF] font-semibold">DAY 3</p>
                                    <h3 class="text-xl font-bold text-[#004AAD]">Customization & Multi-Image</h3>
                                    <p class="text-[#3D3D3D]">Expanded to handle multiple images and added interactive widgets for story customization (tone and length).</p>
                                </div>
                            </div>
                             <div class="absolute left-1/2 -translate-x-1/2 w-8 h-8 bg-[#0094FF] rounded-full border-4 border-white z-20 hidden md:block"></div>
                            <div class="md:w-1/2"></div>
                        </div>
                        <div class="relative md:flex md:flex-row-reverse md:items-center mb-12">
                            <div class="md:w-1/2 text-center md:text-left md:pl-8 z-10">
                                <div class="p-6 bg-white rounded-lg shadow-md">
                                    <p class="text-sm text-[#0094FF] font-semibold">DAY 4</p>
                                    <h3 class="text-xl font-bold text-[#004AAD]">PDF & Audio Export</h3>
                                    <p class="text-[#3D3D3D]">Implemented output features, allowing stories to be saved as PDFs with `reportlab` and MP3s with `gTTS`.</p>
                                </div>
                            </div>
                             <div class="absolute left-1/2 -translate-x-1/2 w-8 h-8 bg-[#0094FF] rounded-full border-4 border-white z-20 hidden md:block"></div>
                            <div class="md:w-1/2"></div>
                        </div>
                         <div class="relative md:flex md:items-center">
                            <div class="md:w-1/2 text-center md:text-right md:pr-8 z-10">
                                <div class="p-6 bg-white rounded-lg shadow-md">
                                    <p class="text-sm text-[#0094FF] font-semibold">DAY 5</p>
                                    <h3 class="text-xl font-bold text-[#004AAD]">Full Web Application</h3>
                                    <p class="text-[#3D3D3D]">Wrapped the entire project into a user-friendly web application using Streamlit, making it accessible and interactive.</p>
                                </div>
                            </div>
                            <div class="absolute left-1/2 -translate-x-1/2 w-8 h-8 bg-[#0094FF] rounded-full border-4 border-white z-20 hidden md:block"></div>
                            <div class="md:w-1/2"></div>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="assessment" class="bg-white rounded-lg shadow-md p-6 md:p-8">
                 <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
                     <div>
                        <h2 class="text-3xl font-bold text-[#004AAD] mb-4">Project Assessment</h2>
                        <p class="text-[#3D3D3D]">The project excels in its implementation of promised features and its selection of technologies. The bar chart provides a comparative look at key assessment areas, highlighting the project's strengths in completeness and technology choices, while also noting areas with potential for future improvement, such as enhancing code modularity for better long-term maintainability.</p>
                    </div>
                    <div class="chart-container h-96 md:h-[450px]">
                        <canvas id="assessmentChart"></canvas>
                    </div>
                </div>
            </section>
            
             <section id="roadmap">
                <h2 class="text-3xl font-bold text-center text-[#004AAD] mb-8">Future Roadmap</h2>
                <div class="max-w-2xl mx-auto bg-white rounded-lg shadow-md p-6">
                    <ul class="space-y-4">
                        <li class="flex items-start">
                            <span class="text-[#0094FF] font-bold text-xl mr-4">🛡️</span>
                            <div>
                                <h3 class="font-bold text-[#004AAD]">Robust Error Handling</h3>
                                <p class="text-[#3D3D3D]">Implement more comprehensive error handling to provide clearer feedback to the user.</p>
                            </div>
                        </li>
                        <li class="flex items-start">
                           <span class="text-[#0094FF] font-bold text-xl mr-4">🧩</span>
                           <div>
                                <h3 class="font-bold text-[#004AAD]">Code Modularity</h3>
                                <p class="text-[#3D3D3D]">Refactor the single script into separate, reusable modules to improve code maintainability.</p>
                           </div>
                        </li>
                        <li class="flex items-start">
                           <span class="text-[#0094FF] font-bold text-xl mr-4">✨</span>
                           <div>
                                <h3 class="font-bold text-[#004AAD]">Enhanced UI/UX</h3>
                                <p class="text-[#3D3D3D]">Improve the Streamlit interface with better loading indicators and a more polished layout.</p>
                           </div>
                        </li>
                    </ul>
                </div>
            </section>

        </main>

        <footer class="text-center mt-16 py-8 border-t border-[#B4E2FF]">
            <p class="text-[#3D3D3D]">Infographic generated based on the analysis of the AI Storyteller project.</p>
        </footer>

    </div>

<script>
    const tooltipTitleCallback = (tooltipItems) => {
        const item = tooltipItems[0];
        let label = item.chart.data.labels[item.dataIndex];
        if (Array.isArray(label)) {
            return label.join(' ');
        }
        return label;
    };

    const processLabels = (labels) => {
        return labels.map(label => {
            if (label.length > 16) {
                const words = label.split(' ');
                const newLabel = [];
                let line = '';
                words.forEach(word => {
                    if ((line + word).length > 16) {
                        newLabel.push(line.trim());
                        line = '';
                    }
                    line += word + ' ';
                });
                newLabel.push(line.trim());
                return newLabel;
            }
            return label;
        });
    };

    const techStackCtx = document.getElementById('techStackChart').getContext('2d');
    new Chart(techStackCtx, {
        type: 'doughnut',
        data: {
            labels: ['google-generativeai', 'Transformers (BLIP)', 'gTTS', 'ReportLab', 'Streamlit'],
            datasets: [{
                label: 'Technology Stack',
                data: [20, 20, 20, 20, 20],
                backgroundColor: ['#004AAD', '#0094FF', '#B4E2FF', '#60A5FA', '#3B82F6'],
                borderColor: '#FFFFFF',
                borderWidth: 3
            }]
        },
        options: {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    position: 'top',
                },
                tooltip: {
                    callbacks: {
                        title: tooltipTitleCallback
                    }
                }
            }
        }
    });

    const assessmentCtx = document.getElementById('assessmentChart').getContext('2d');
    const assessmentLabels = ['Feature Completeness', 'Technology Choices', 'Code Structure', 'UI/UX'];
    new Chart(assessmentCtx, {
        type: 'bar',
        data: {
            labels: processLabels(assessmentLabels),
            datasets: [{
                label: 'Assessment Score (out of 100)',
                data: [100, 95, 75, 70],
                backgroundColor: ['#004AAD', '#0094FF', '#60A5FA', '#B4E2FF'],
                borderColor: ['#004AAD', '#0094FF', '#60A5FA', '#B4E2FF'],
                borderWidth: 1,
                borderRadius: 5,
            }]
        },
        options: {
            indexAxis: 'y',
            responsive: true,
            maintainAspectRatio: false,
            scales: {
                x: {
                    beginAtZero: true,
                    max: 100
                }
            },
            plugins: {
                legend: {
                    display: false
                },
                tooltip: {
                    callbacks: {
                        title: tooltipTitleCallback
                    }
                }
            }
        }
    });
</script>

</body>
</html>
