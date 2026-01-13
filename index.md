---
layout: default
title: Pruddieverse
---

<!-- Hero Section -->
<div class="flex flex-col items-center space-y-6">

  <!-- Headshot -->
  <img data-aos="fade-up" src="/assets/images/headshot.jpg" alt="Prudence Anumudu" 
       class="rounded-2xl w-48 md:w-64 lg:w-72 object-cover">

  <!-- Hero Statement -->
  <h1 data-aos="fade-up" class="text-4xl font-bold">
    Building the Pruddieverse
  </h1>
  <p data-aos="fade-up" data-aos-delay="200" class="text-lg max-w-xl">
    I don’t just solve technical problems, I bridge the gap between human needs and automated solutions.
  </p>

  <!-- Skills Cards -->
  <div data-aos="fade-up" data-aos-delay="400" class="grid grid-cols-2 sm:grid-cols-4 gap-4 mt-6 w-full max-w-4xl">

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">⚡</div>
      <span>AWS</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🧩</div>
      <span>K8S</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🏗️</div>
      <span>Terraform</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🤖</div>
      <span>Ansible</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🐳</div>
      <span>Docker</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">💻</div>
      <span>Bash</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🔗</div>
      <span>Git</span>
    </div>

    <div class="bg-gray-800 rounded-lg p-6 flex flex-col items-center justify-center transform transition hover:scale-110 hover:bg-gray-700">
      <div class="w-12 h-12 mb-2 flex items-center justify-center text-3xl animate-bounce">🤹</div>
      <span>Jenkins</span>
    </div>

  </div>

  <!-- Explore Button -->
  <a data-aos="fade-up" data-aos-delay="600" href="/projects.html"
     class="mt-10 inline-block px-6 py-3 bg-blue-600 rounded-lg text-white font-semibold hover:bg-blue-500 transition">
    🚀 Explore the Laboratory
  </a>

</div>

<!-- Skills Section -->
<div class="flex gap-4 justify-center mt-8 flex-wrap">

  <div class="skill-card">
    <div class="skill-icon">☁️</div>
    <span>AWS</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">🕹️</div>
    <span>K8S</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">🏗️</div>
    <span>Terraform</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">🤖</div>
    <span>Ansible</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">🐳</div>
    <span>Docker</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">&gt;_</div>
    <span>Bash</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">🌿</div>
    <span>Git</span>
  </div>

  <div class="skill-card">
    <div class="skill-icon">⚙️</div>
    <span>Jenkins</span>
  </div>

</div>

<!-- Jenkins Fix -->
<script>
  document.addEventListener("DOMContentLoaded", () => {
    document.querySelectorAll(".skill-card span")
      .forEach(card => {
        if (card.textContent.includes("Jenkins")) {
          card.previousElementSibling.classList.add("jenkins");
        }
      });
  });
</script>

<!-- Apply hero-to-skills spacing -->
<script>
  document.addEventListener("DOMContentLoaded", () => {
    const skillsGrid = document.querySelector(".grid");
    if (skillsGrid) {
      skillsGrid.classList.add("hero-spacing");
    }
  });
</script>
