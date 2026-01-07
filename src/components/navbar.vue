<script setup>
</script>

<template>
 <nav class="navbar">
    <div class="brand">
      <a href="#">StoryArc <span>Flims</span></a>
    </div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>
</template>

<style scoped>
    /* Navbar styles */
    .navbar {
        display: flex;
        justify-content: space-between; /* Space between brand and nav links */
        align-items: center;
        background-color: #000; /* Black background */
        padding: 10px 20px;
    }

    .brand a {
        color: white;
        text-decoration: none;
        font-size: 24px;
        font-weight: bold;
        font-family: Georgia, 'Times New Roman', Times, serif;
        margin-left: 1rem;
    }
    .brand a span {
        color: #ff5733; /* Accent color for "Flims" */
    }
    .navbar ul {
        list-style-type: none;
        display: flex;
        margin: 0;
    }

    .navbar ul li {
        margin: 0 20px;
    }

    .navbar ul li a {
        color: white;
        text-decoration: none;
        font-size: 18px;
        padding: 10px 5px;
        display: inline-block;
        transition: background-color 0.3s ease; /* Smooth transition */
    }

    .navbar ul li a:hover {
        background-color: #444; /* Dark gray on hover */
        border-radius: 4px;
    }

</style>