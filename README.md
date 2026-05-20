# Lunch-table
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Our Lunch Table</title>

<style>
body {
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
    background: #0f172a;
    color: white;
    scroll-behavior: smooth;
}

/* HEADER */
header {
    text-align: center;
    padding: 60px 20px 40px;
}

h1 {
    font-size: 48px;
    margin-bottom: 20px;
}

/* BUTTONS */
.nav-buttons {
    display: flex;
    justify-content: center;
    gap: 20px;
}

button {
    padding: 12px 24px;
    font-size: 18px;
    border-radius: 8px;
    border: none;
    cursor: pointer;
}

/* SECTIONS */
section {
    padding: 80px 20px;
    max-width: 800px;
    margin: auto;
}

h2 {
    font-size: 36px;
    margin-bottom: 15px;
}
</style>
</head>

<body>

<header>
    <h1>Our Lunch Table</h1>
    <div class="nav-buttons">
        <button onclick="scrollToSection('about')">About</button>
        <button onclick="scrollToSection('members')">Our Members</button>
    </div>
</header>

<section id="about">
    <h2>About</h2>
    <p>
        This is where you write about your lunch table, what you guys do,
        jokes, traditions, or anything you want people to know.
    </p>
</section>

<section id="members">
    <h2>Our Members</h2>
    <p>
        Put the names of everyone here and maybe a short description for each.
    </p>
</section>

<script>
function scrollToSection(id) {
    document.getElementById(id).scrollIntoView();
}
</script>

</body>
</html>