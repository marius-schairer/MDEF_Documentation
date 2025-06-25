<!-- filepath: /Users/mars/Documents/GitHub/MDEF_Documentation/docs/term3/LAIAProject.md -->
<div class="breadcrumb">
    <a href="/">Home</a> <span class="breadcrumb-separator">/</span> 
    <a href="/MDEF_Docmentation/term3">Term 3</a> <span class="breadcrumb-separator">/</span> 
    <span>LAIA Project</span>
</div>

<style>
/* LAIA-specific styles */
:root {
  --accent-color: #a855f7;
  --accent-color-hover: rgba(168, 85, 247, 0.8);
  --accent-color-light: rgba(168, 85, 247, 0.1);
  --text-primary: #1f2937;
  --text-secondary: #4b5563;
  --text-muted: #6b7280;
  --bg-primary: #f9fafb;
  --bg-secondary: #ffffff;
  --card-bg: white;
  --card-border: #e5e7eb;
}

.accent-tag {
  background-color: var(--accent-color);
  color: white;
}

.hero-stat-card {
  background-color: var(--card-bg);
  border: 1px solid var(--card-border);
}

.text-theme-primary { color: var(--text-primary); }
.text-theme-secondary { color: var(--text-secondary); }
.text-theme-muted { color: var(--text-muted); }
.bg-bg-primary { background-color: var(--bg-primary); }
.bg-card-bg { background-color: var(--card-bg); }

.font-human { font-family: "Inter", sans-serif; }
.font-machine { font-family: "JetBrains Mono", monospace; }

.hero-nav-btn {
  transition: all 0.3s ease;
  color: var(--text-muted);
  border-color: var(--card-border);
  text-decoration: none;
}

.hero-nav-btn:hover {
  background-color: var(--accent-color-light);
  border-color: var(--accent-color);
  color: var(--accent-color);
}

.collaborator-avatar {
  border-radius: 50%;
}

.github-icon {
  filter: var(--icon-filter, none);
}
</style>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/icon?family=Material+Symbols+Outlined" rel="stylesheet">

<!-- Article Hero Section -->
<section class="bg-bg-primary py-16 md:py-24">
  <div class="max-w-7xl mx-auto px-6">
    <!-- Project Hero Section -->
    <div class="flex flex-col mb-16 mt-6">
      <div class="flex flex-col md:flex-row gap-8">
        <!-- Project Details -->
        <div class="md:w-2/5">
          <h1 class="text-5xl md:text-6xl mb-6 text-theme-primary font-human">LAIA</h1>
          <p class="text-xl text-theme-secondary mb-6 font-human leading-relaxed">
            A 6-month community intervention exploring local AI versus global search systems in Barcelona's El
            Clot neighborhood. Investigating how AI can serve local communities rather than extracting value for
            distant algorithms.
          </p>

          <!-- Tags -->
          <div class="flex flex-wrap gap-2 mb-8">
            <span class="accent-tag px-3 py-1 rounded-full text-sm text-white font-machine">Local AI</span>
            <span class="accent-tag px-3 py-1 rounded-full text-sm text-white font-machine">Community</span>
            <span class="accent-tag px-3 py-1 rounded-full text-sm text-white font-machine">RAG</span>
            <span class="accent-tag px-3 py-1 rounded-full text-sm text-white font-machine">Barcelona</span>
            <span class="accent-tag px-3 py-1 rounded-full text-sm text-white font-machine">Neighborhood</span>
          </div>
        </div>
        <!-- Project Stats -->
        <div class="flex flex-col md:w-3/5">
          <div class="grid grid-cols-2 md:grid-cols-4 gap-4 h-min mb-8">
            <div class="hero-stat-card p-4 rounded-2xl">
              <div class="text-sm text-theme-muted font-machine">When?</div>
              <div class="text-xl text-theme-primary font-semibold font-human">2023 - Now</div>
            </div>
            <div class="hero-stat-card p-4 rounded-2xl h-min">
              <div class="text-sm text-theme-muted font-machine">Stage</div>
              <div class="text-xl text-theme-primary font-semibold font-human">Prototype</div>
            </div>
            <div class="hero-stat-card p-4 rounded-2xl h-min">
              <a href="https://github.com/laia-github" target="_blank"
                class="text-theme-primary hover:text-accent transition-colors flex">
                <div class="flex flex-row">
                  <div class="rounded-full overflow-hidden w-12 h-12 mr-4 bg-card-bg flex items-center justify-center">
                    <img src="../images/Logos/github.png" alt="GitHub" class="w-6 h-6 github-icon" />
                  </div>
                  <div>
                    <div class="text-sm text-theme-muted">GitHub</div>
                    <div class="text-lg text-theme-primary">Repository</div>
                  </div>
                </div>
              </a>
            </div>
            <div class="hero-stat-card p-4 rounded-lg h-min">
              <a href="https://laia-github.github.io/LaiaWeb/" target="_blank"
                class="text-theme-primary hover:text-accent transition-colors flex">
                <div>
                  <div class="text-sm text-theme-muted">Explore</div>
                  <div class="text-lg text-theme-primary">LAIA Project</div>
                </div>
              </a>
            </div>
          </div>

          <!-- Collaborators Section -->
          <div class="flex flex-col gap-8">
            <div class="space-y-4">
              <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="flex flex-col h-full">
                  <div class="flex flex-row items-center">
                    <div class="w-16 h-16 flex-shrink-0 rounded-full overflow-hidden mr-4">
                      <img src="../images/Laia/nuria-placeholder.png" alt="Nuria Valsells"
                        class="w-full h-full object-cover collaborator-avatar">
                    </div>
                    <div class="flex flex-col">
                      <h4 class="text-xl font-bold text-theme-primary">Nuria Valsells</h4>
                      <p class="text-theme-muted">Communication & Design</p>
                    </div>
                  </div>
                </div>
                <div class="flex flex-col h-full">
                  <div class="flex flex-row items-center">
                    <div class="w-16 h-16 flex-shrink-0 rounded-full overflow-hidden mr-4">
                      <img src="../images/Logos/IAAC.png" alt="IAAC"
                        class="w-full h-full object-cover collaborator-avatar">
                    </div>
                    <div class="flex flex-col">
                      <h4 class="text-xl font-bold text-theme-primary">IAAC</h4>
                      <p class="text-theme-muted">Hosting Institution</p>
                    </div>
                  </div>
                </div>
                <div class="flex flex-col h-full">
                  <div class="flex flex-row items-center">
                    <div class="w-16 h-16 flex-shrink-0 rounded-full overflow-hidden mr-4">
                      <img src="../images/AboutMe/Profile.jpg" alt="Marius Schairer"
                        class="w-full h-full object-cover collaborator-avatar">
                    </div>
                    <div class="flex flex-col">
                      <h4 class="text-xl font-bold text-theme-primary">Marius Schairer</h4>
                      <p class="text-theme-muted">Prototyping & Development</p>
                    </div>
                  </div>
                </div>
                <div class="flex flex-col h-full">
                  <div class="flex flex-row items-center">
                    <div class="w-16 h-16 flex-shrink-0 rounded-full overflow-hidden mr-4">
                      <img src="../images/Laia/akasha-placeholder.png" alt="Akasha Hub"
                        class="w-full h-full object-cover collaborator-avatar">
                    </div>
                    <div class="flex flex-col">
                      <h4 class="text-xl font-bold text-theme-primary">Akasha Hub</h4>
                      <p class="text-theme-muted">Collaboration & Exhibition</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Section Navigation -->
      <div class="flex flex-wrap gap-4 my-16 justify-center">
        <a href="#concept" class="hero-nav-btn px-4 py-2 border rounded-full transition-all flex items-center">
          Concept <span class="material-symbols-outlined ml-1 text-sm">keyboard_arrow_down</span>
        </a>
        <a href="#setup" class="hero-nav-btn px-4 py-2 border rounded-full transition-all flex items-center">
          Setup <span class="material-symbols-outlined ml-1 text-sm">keyboard_arrow_down</span>
        </a>
        <a href="#intervention" class="hero-nav-btn px-4 py-2 border rounded-full transition-all flex items-center">
          Intervention <span class="material-symbols-outlined ml-1 text-sm">keyboard_arrow_down</span>
        </a>
        <a href="#highlights" class="hero-nav-btn px-4 py-2 border rounded-full transition-all flex items-center">
          Highlights <span class="material-symbols-outlined ml-1 text-sm">keyboard_arrow_down</span>
        </a>
      </div>

      <!-- Main project image -->
      <div class="mt-8">
        <div class="rounded-2xl overflow-hidden shadow-xl">
          <img src="../images/Laia/Final_Cover.png" alt="LAIA Project - Local AI in El Clot neighborhood"
            class="w-full h-auto object-cover">
        </div>
        <div class="text-center mt-4">
          <p class="text-sm text-theme-muted font-human">Local AI systems serving the El Clot neighborhood community</p>
        </div>
      </div>
    </div>
  </div>
</section>

## Concept {#concept}
*Local AI vs global extraction*

LAIA emerged from a critical question: **What happens when AI systems serve local communities instead of extracting data for global platforms?** Through a 6-month collaboration with Nuria at IAAC/Fablab Barcelona, we explored this tension between local and global AI in El Clot, a vibrant neighborhood in Barcelona.

The project challenged the dominant paradigm where AI search systems like Google funnel local queries through global algorithms, extracting value from communities while returning generic results. Instead, we investigated how retrieval-augmented generation (RAG) could create neighborhood-specific AI systems.

Working directly with residents, students, and local organizations, LAIA became both a technical experiment and a community intervention—exploring how AI can amplify local knowledge rather than replace it with algorithmic abstractions.

![Community engagement in El Clot neighborhood](../images/Laia/LAIAExhibition.png)

## Setup {#setup}
*Technical infrastructure and community partnerships*

### Technical Infrastructure
We built a localized RAG system using neighborhood-specific data sources: local business directories, community event listings, resident interviews, and historical documentation about El Clot. The system prioritized hyperlocal knowledge over global search results.

Rather than relying on massive datasets, we created a curated knowledge base that reflected the lived experience of the neighborhood—from the best local bakeries to community organizing strategies.

### Community Partnership
The collaboration with IAAC/Fablab Barcelona provided both technical resources and deep community connections. Nuria's local expertise was essential for navigating neighborhood dynamics and building trust with residents.

We established partnerships with local schools, adult education centers, and community organizations to ensure the project served real needs rather than imposing external solutions.

![Local data collection and curation process](../images/Laia/LAIAContext.png)

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/948664337?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write" style="position:absolute;top:0;left:0;width:100%;height:100%;" title="LAIA, insta video draft"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

## Intervention {#intervention}
*Community workshops and public engagement*

### Student Workshops
We conducted hands-on workshops with local students, teaching them to question AI systems and understand how algorithms shape their access to information. Students learned to compare local AI responses with global search results, developing critical digital literacy skills.

### Adult School Engagement
Adult education sessions focused on practical applications: How could local AI help with job searches, housing information, or navigating city services? Participants shared their expertise while learning to interrogate algorithmic decision-making.

### Public Exhibition
LAIA was exhibited at the ACT Festival at Akasha Hub, demonstrating the project's findings to a broader audience. The exhibition showcased the contrast between generic AI responses and hyperlocal knowledge, sparking conversations about digital sovereignty and community autonomy.

![Workshop participants analyzing AI responses](../images/Laia/LAIACart.png)

## Highlights & Insights {#highlights}
*Key learnings and project impact*

### Community Knowledge vs. Global Algorithms
The project revealed how global AI systems often miss nuanced local knowledge—the informal networks, cultural practices, and community wisdom that actually make neighborhoods function. Local AI provided more relevant, contextual responses to resident queries.

### Digital Sovereignty in Practice
LAIA demonstrated that communities can develop their own AI tools rather than accepting algorithmic colonization. By maintaining control over data and training processes, neighborhoods can preserve their autonomy while benefiting from AI assistance.

### Educational Impact
Students and adults developed critical thinking skills about AI systems, learning to question algorithmic authority and understand how technology shapes their daily lives. The workshops created lasting awareness about digital literacy and technological choice.

### Scalable Model
The LAIA methodology provides a template for other communities seeking technological autonomy. The project's approach—combining technical development with community engagement—offers a replicable framework for local AI initiatives.

## Interactive Platform

Experience LAIA's community knowledge system and contribute your own local insights:

<iframe style='border:none;width:100%;' height='1200px' src='https://laia-github.github.io/LaiaWeb/'></iframe>

## Connect with LAIA

- **Website**: [LAIA Platform](https://laia-github.github.io/LaiaWeb/)
- **Instagram**: [@laia.collectiu](https://www.instagram.com/laia.collectiu/)
- **GitHub**: [LAIA Repository](https://github.com/laia-github)

---

*LAIA continues to evolve as a model for community-controlled AI, demonstrating that technology can serve local needs while preserving neighborhood autonomy and cultural identity.*
