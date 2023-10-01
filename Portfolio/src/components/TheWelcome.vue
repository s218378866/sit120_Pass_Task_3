<template>
  <section class="home-page">
    <!-- <div class="profile-image">
      <img src="../assets/images/alison-wang-mou0S7ViElQ-unsplash.jpg" alt="Your Name" class="hover-effect">
    </div> -->

    <div class="heading">
      <h1>This is my Projects</h1>
    </div>

    <!-- First Project--------------------------------------------------------------- -->
    <div class="project-image">
      <img src="../assets/images/devin-avery-BRVqq2uak4E-unsplash.jpg" alt="Your Name" class="hover-effect">
    </div>
    <div class="home-content">
      <h1>This is the Prejcet 1</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      
      <p>
        If you want to konw more, feel free to <a href="mailto:your-email@example.com">reach out</a>!
      </p>
    </div>

    <!-- Second Project--------------------------------------------------------------- -->
    <div class="project-image">
      <img src="../assets/images/eniko-kis-KsLPTsYaqIQ-unsplash.jpg" alt="Your Name" class="hover-effect">
    </div>
    <div class="home-content">
      <h1>This is the Prejcet 2</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      
      <p>
        If you want to konw more, feel free to <a href="mailto:your-email@example.com">reach out</a>!
      </p>
    </div>

     <!-- Third Project--------------------------------------------------------------- -->
     <div class="project-image">
      <img src="../assets/images/kelly-sikkema-1Pgq9ZpIatI-unsplash.jpg" alt="Your Name" class="hover-effect">
    </div>
    <div class="home-content">
      <h1>This is the Prejcet 3</h1>
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </p>
      
      <p>
        If you want to konw more, feel free to <a href="mailto:your-email@example.com">reach out</a>!
      </p>
    </div>
  </section>
</template>
 
<script setup>
// You can add any reactive properties or methods if needed.
</script>
 
<style scoped>
.home-page {
  display: grid;
  grid-template-columns: auto;
  justify-content: center;
  align-items: center;
  padding: 40px 0;
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  background-color: #f4f4f4;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
 
.project-image {
  flex: 1;
  padding-left: 25px;
  padding-top: 50px;
  padding-bottom: 50px;
  width: 120%;
  
  justify-content: center;
}
 
.project-image img.hover-effect {
  max-width: 80%;
  transition: transform 0.3s, box-shadow 0.3s;
}
 
.project-image img.hover-effect:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}
 
.home-content {
  flex: 2;
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
}
 
.heading {
  padding-left: 20px;
  padding-right: 20px;
  text-align: center;
}

.heading h1 {
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
  font-size: 3.5em;
  margin-bottom: 20px;
}

.home-content h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}
 
.home-content p {
  margin-bottom: 20px;
  line-height: 1.6;
}
 
.home-content a {
  color: #e74c3c;
  text-decoration: none;
  transition: color 0.3s;
}
 
.home-content a:hover {
  color: #c0392b;
}
 
.download-btn {
  display: inline-block;
  background-color: #e74c3c;
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s;
}
 
.download-btn:hover {
  background-color: #c0392b;
}
</style>