# Jackson-Site-Plan---HTML-Skeleton
My HTML Skeleton
[about.html](https://github.com/user-attachments/files/33632948/about.html)


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Learn about Albert and how to contact him.">
  <title>About / Contact | Albert's Portfolio</title>
  <style>
    :root { --navy: #0B1220; --teal: #0D9488; --light: #F1F5F9; --white: #FFFFFF; }
    * { box-sizing: border-box; }
    body { margin: 0; font-family: Arial, sans-serif; line-height: 1.6; color: var(--navy); background: var(--light); }
    header, footer { background: var(--navy); color: var(--white); padding: 1rem 6%; }
    nav a { color: var(--white); margin-right: 1rem; text-decoration: none; }
    nav a:hover, nav a:focus { color: #5EEAD4; }
    main { max-width: 960px; margin: 2rem auto; padding: 0 1.25rem; }
    section { background: var(--white); padding: 2rem; margin-bottom: 1.25rem; border-radius: 12px; }
    .accent { color: var(--teal); }
    footer { margin-top: 3rem; }
  </style>
</head>
<body>
  <header>
    <p><strong>ALBERT / PORTFOLIO</strong></p>
    <nav aria-label="Main navigation">
      <a href="index.html">Home</a>
      <a href="projects.html">Projects / Work</a>
      <a href="about.html" aria-current="page">About / Contact</a>
    </nav>
  </header>

  <main>
    <section>
      <p class="accent">MY STORY</p>
      <h1>About Me</h1>
      <p>I'm a student from Los Angeles working toward a future in cybersecurity and information technology. I'm interested in learning how computers and networks work and how to help keep systems secure.</p>
    </section>

    <section>
      <h2>Skills and Goals</h2>
      <h3>Skills I'm developing</h3>
      <ul>
        <li>HTML and web page structure</li>
        <li>Computer and cybersecurity fundamentals</li>
        <li>Communication, teamwork, and problem-solving</li>
      </ul>
      <h3>My goal</h3>
      <p>My goal is to keep learning, complete hands-on projects, and build the skills needed for an entry-level IT or cybersecurity role.</p>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Add a professional email address or public profile link here when you're ready to share it.</p>
      <!-- Replace the example below with your own public contact details before publishing. -->
      <p>Email: <a href="mailto:your.email@example.com">your.email@example.com</a> (placeholder)</p>
      <p>Professional profile: <a href="#">Add your profile link</a> (placeholder)</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Albert's Portfolio. Built as a learning project.</p>
  </footer>
</body>
</html>
[index.html](https://github.com/user-attachments/files/33632962/index.html)
[projects.html](https://github.com/user-attachments/files/33632973/projects.html)
[wireframes.txt](https://github.com/user-attachments/files/33633009/wireframes.txt)
PERSONAL PORTFOLIO WIREFRAME NOTES

COLOR / TYPE
- Navy (#0B1220), teal (#0D9488), light gray (#F1F5F9), white (#FFFFFF)
- Arial or another readable sans-serif font

PAGE 1 — HOME
[Header: Portfolio name]
[Navigation: Home | Projects / Work | About / Contact]
[Hero: Welcome message, name, major/career direction, button to projects]
[Section: Current focus / skills / goals]
[Footer: copyright]

PAGE 2 — PROJECTS / WORK
[Header + same navigation]
[Page title and short introduction]
[Project cards: title, skills, description, status]
[Footer: copyright]

PAGE 3 — ABOUT / CONTACT
[Header + same navigation]
[About me / background]
[Skills and goals]
[Contact details and professional links]
[Footer: copyright]
