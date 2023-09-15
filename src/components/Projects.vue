<script setup></script>
<template>
  <section id="projects">
    <p class="section__text__p1">Browse My Recent</p>
    <h1 class="title">Projects</h1>
    <div class="experience-details-container">
      <div class="about-containers">
        <div class="details-container color-container">
          <div class="article-container">
            <img
              src="https://cdn.sanity.io/images/5mm9u6u8/production/0578c0a17e8a223a1aec2e79695df7bd786c2f21-800x800.png"
              alt="Project 1"
              class="project-img"
            />
          </div>
          <h2 class="experience-sub-title project-title">Project One</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Live Demo
            </button>
          </div>
        </div>
        <div class="details-container color-container">
          <div class="article-container">
            <img
              src="https://cdn.sanity.io/images/5mm9u6u8/production/0578c0a17e8a223a1aec2e79695df7bd786c2f21-800x800.png"
              alt="Project 2"
              class="project-img"
            />
          </div>
          <h2 class="experience-sub-title project-title">Project Two</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Live Demo
            </button>
          </div>
        </div>
        <div class="details-container color-container">
          <div class="article-container">
            <img
              src="https://cdn.sanity.io/images/5mm9u6u8/production/0578c0a17e8a223a1aec2e79695df7bd786c2f21-800x800.png"
              alt="Project 3"
              class="project-img"
            />
          </div>
          <h2 class="experience-sub-title project-title">Project Three</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Live Demo
            </button>
          </div>
        </div>
        <div class="details-container color-container">
          <div class="article-container">
            <img
              src="https://cdn.sanity.io/images/5mm9u6u8/production/0578c0a17e8a223a1aec2e79695df7bd786c2f21-800x800.png"
              alt="Project 3"
              class="project-img"
            />
          </div>
          <h2 class="experience-sub-title project-title">Project Three</h2>
          <div class="btn-container">
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Github
            </button>
            <button
              class="btn btn-color-2 project-btn"
              onclick="location.href='https://github.com/'"
            >
              Live Demo
            </button>
          </div>
        </div>
      </div>
    </div>
    <img
      src="./assets/arrow.png"
      alt="Arrow icon"
      class="icon arrow"
      onclick="location.href='./#contact'"
    />
  </section>
</template>

<style scoped>
#projects {
  position: relative;
}

.about-containers,
.about-details-container {
  display: grid;
  
}

.experience-sub-title {
  color: rgb(85, 85, 85);
  font-weight: 600;
  font-size: 1.75rem;
  margin-bottom: 2rem;
  text-align: center;
}

.experience-details-container {
  display: flex;
  justify-content: center;
  flex-direction: column;
}

a,
.btn {
  transition: all 300ms ease;
}

.color-container {
  border-color: rgb(163, 163, 163);
  background: rgb(250, 250, 250);
}

.project-img {
  border-radius: 2rem;
  width: 10%;
  height: 10%;
}

.project-title {
  margin: 1rem;
  color: black;
}

.project-btn {
  color: black;
  border-color: rgb(163, 163, 163);
}

.icon {
  cursor: pointer;
  height: 2rem;
}

.arrow {
  position: absolute;
  right: -5rem;
  bottom: 2.5rem;
}

p {
  color: rgb(85, 85, 85);
}
.title {
  font-size: 3rem;
  text-align: center;
}

.btn-container {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

.btn {
  font-weight: 600;
  transition: all 300ms ease;
  padding: 1rem;
  width: 8rem;
  border-radius: 2rem;
}

.btn-color-1,
.btn-color-2 {
  border: rgb(53, 53, 53) 0.1rem solid;
}

.btn-color-1:hover,
.btn-color-2:hover {
  cursor: pointer;
}

.btn-color-1,
.btn-color-2:hover {
  background: rgb(53, 53, 53);
  color: white;
}

.btn-color-1:hover {
  background: rgb(0, 0, 0);
}

.btn-color-2 {
  background: none;
}

.btn-color-2:hover {
  border: rgb(255, 255, 255) 0.1rem solid;
}

.btn-container {
  gap: 1rem;
}

.article-container {
  display: flex;
  text-align: initial;
  flex-wrap: wrap;
  flex-direction: row;
  gap: 2.5rem;
  justify-content: space-around;
}

article {
  display: flex;
  width: 10rem;
  justify-content: space-around;
  gap: 0.5rem;
}

article .icon {
  cursor: default;
}
</style>
