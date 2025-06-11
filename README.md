<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anas Sadki - Profile Banner</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'JetBrains Mono', monospace;
            background-color: #120c18;
            color: #d9c9e6;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 1rem;
        }
        .profile-banner {
            background: rgba(23, 16, 32, 0.6);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 1rem;
            padding: 0.75rem 1.5rem;
            display: flex;
            align-items: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            justify-content: center;
            box-shadow: 0 0 20px rgba(199, 125, 255, 0.1);
        }
        .profile-pic {
            width: 64px;
            height: 64px;
            border-radius: 50%;
            border: 2px solid #c77dff;
            object-fit: cover;
            padding: 2px;
        }
        .description-text {
            font-size: 1.125rem;
            font-weight: 700;
            color: #e0cff0;
            text-shadow: 0 0 5px rgba(255,255,255,0.2);
        }
        .tech-logos i {
            font-size: 1.75rem;
            color: #8b809a;
            transition: color 0.3s, transform 0.3s;
        }
        .tech-logos i:hover {
            color: #c77dff;
            transform: scale(1.1);
        }
        .divider {
            width: 1px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body>
    <div class="profile-banner">
        <!-- Profile Picture -->
        <img 
            src="https://placehold.co/128x128/120c18/c77dff?text=AS" 
            alt="Anas Sadki Profile Picture" 
            class="profile-pic"
            onerror="this.onerror=null;this.src='https://placehold.co/128x128/1a101f/d9c9e6?text=Error';"
        >
        
        <!-- Description Text with Emojis -->
        <div class="description-text">
            Anas Sadki | Moroccan CS Student 🇲🇦 | Future 1337 Coder 🎯 | Bridging Philosophy & Code 🧠🚀
      <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anas Sadki - Profile Banner</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        body {
            font-family: 'JetBrains Mono', monospace;
            background-color: #120c18;
            color: #d9c9e6;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            padding: 1rem;
        }
        .profile-banner {
            background: rgba(23, 16, 32, 0.6);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
            border-radius: 1rem;
            padding: 0.75rem 1.5rem;
            display: flex;
            align-items: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            justify-content: center;
            box-shadow: 0 0 20px rgba(199, 125, 255, 0.1);
        }
        .profile-pic {
            width: 64px;
            height: 64px;
            border-radius: 50%;
            border: 2px solid #c77dff;
            object-fit: cover;
            padding: 2px;
        }
        .description-text {
            font-size: 1.125rem;
            font-weight: 700;
            color: #e0cff0;
            text-shadow: 0 0 5px rgba(255,255,255,0.2);
        }
        .tech-logos i {
            font-size: 1.75rem;
            color: #8b809a;
            transition: color 0.3s, transform 0.3s;
        }
        .tech-logos i:hover {
            color: #c77dff;
            transform: scale(1.1);
        }
        .divider {
            width: 1px;
            height: 40px;
            background-color: rgba(255, 255, 255, 0.1);
        }
    </style>
</head>
<body>
    <div class="profile-banner">
        <!-- Profile Picture -->
        <img 
            src="https://placehold.co/128x128/120c18/c77dff?text=AS" 
            alt="Anas Sadki Profile Picture" 
            class="profile-pic"
            onerror="this.onerror=null;this.src='https://placehold.co/128x128/1a101f/d9c9e6?text=Error';"
        >
        
        <!-- Description Text with Emojis -->
        <div class="description-text">
            Anas Sadki | Moroccan CS Student 🇲🇦 | Future 1337 Coder 🎯 | Bridging Philosophy & Code 🧠🚀
        </div>
        
        <!-- Divider -->
        <div class="divider hidden md:block"></div>
        
        <!-- Programming Logos -->
        <div class="tech-logos flex items-center gap-4">
            <i class="fa-brands fa-linux" title="Linux"></i>
            <i class="fa-brands fa-ubuntu" title="Ubuntu"></i>
            <i class="fa-brands fa-python" title="Python"></i>
            <i class="fas fa-terminal" title="Shell/Bash"></i>
        </div>
    </div>
</body>
</html>
  </div>
        
        <!-- Divider -->
        <div class="divider hidden md:block"></div>
        
        <!-- Programming Logos -->
        <div class="tech-logos flex items-center gap-4">
            <i class="fa-brands fa-linux" title="Linux"></i>
            <i class="fa-brands fa-ubuntu" title="Ubuntu"></i>
            <i class="fa-brands fa-python" title="Python"></i>
            <i class="fas fa-terminal" title="Shell/Bash"></i>
        </div>
    </div>
</body>
</html>
How it Works:
Profile Picture: A stylish placeholder with your initials, "AS". You can easily replace the src with a real photo URL.
Central Description: This is the core of the banner. It's a bold, single line that quickly tells everyone who you are, where you're from, and what your mission is. The emojis (🇲🇦 🎯 🧠 🚀) add personality and visual flair.
Tech Stack: A clean set of logos for Linux, Ubuntu, Python, and Shell/Terminal represents your current technical focus. Hovering over them reveals a color change and a slight zoom effect.
Sleek Design: The entire banner has the same "glass" effect as your CV, ensuring a consistent and professional personal brand. It's fully responsive and will look great on different screen sizes.
![Screenshot 2025-06-11 221327](https://github.com/user-attachments/assets/74cda854-a265-458a-b024-03f0d77abbfe)
