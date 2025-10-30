# CDCI
This is our website
<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chandan Digital Computer Institute</title>
  <script src="/_sdk/element_sdk.js"></script>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
        body {
            box-sizing: border-box;
        }
        
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        
        .card-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        .smooth-scroll {
            scroll-behavior: smooth;
        }
        
        .fade-in {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease, transform 0.6s ease;
        }
        
        .fade-in.visible {
            opacity: 1;
            transform: translateY(0);
        }
    </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
 </head>
 <body class="smooth-scroll"><!-- Navigation -->
  <nav class="fixed top-0 w-full z-50 bg-white shadow-lg">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex justify-between items-center h-16">
     <div class="flex items-center">
      <div class="flex-shrink-0">
       <h1 id="nav-institute-name" class="text-xl font-bold text-gray-800">Chandan Digital Computer Institute</h1>
      </div>
     </div>
     <div class="hidden md:block">
      <div class="ml-10 flex items-baseline space-x-4"><a href="#home" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Home</a> <a href="#about" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">About</a> <a href="#courses" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Courses</a> <a href="#contact" class="text-gray-700 hover:text-blue-600 px-3 py-2 rounded-md text-sm font-medium transition-colors">Contact</a>
      </div>
     </div>
     <div class="md:hidden"><button id="mobile-menu-btn" class="text-gray-700 hover:text-blue-600 focus:outline-none">
       <svg class="h-6 w-6" fill="none" viewbox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
       </svg></button>
     </div>
    </div>
   </div><!-- Mobile menu -->
   <div id="mobile-menu" class="md:hidden hidden bg-white border-t">
    <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3"><a href="#home" class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium">Home</a> <a href="#about" class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium">About</a> <a href="#courses" class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium">Courses</a> <a href="#contact" class="text-gray-700 hover:text-blue-600 block px-3 py-2 rounded-md text-base font-medium">Contact</a>
    </div>
   </div>
  </nav><!-- Hero Section -->
  <section id="home" class="gradient-bg min-h-screen flex items-center justify-center pt-16">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
    <div class="fade-in">
     <h1 id="hero-title" class="text-4xl md:text-6xl font-bold text-white mb-6">Master Digital Skills for Tomorrow</h1>
     <p id="hero-subtitle" class="text-xl md:text-2xl text-blue-100 mb-8 max-w-3xl mx-auto">Join Chandan Digital Computer Institute and unlock your potential with comprehensive computer education and digital literacy programs</p>
     <p id="tagline" class="text-lg text-blue-200 mb-8">Empowering Students with Digital Excellence</p><button id="cta-button" class="bg-white text-blue-600 font-semibold py-4 px-8 rounded-full text-lg hover:bg-blue-50 transition-colors shadow-lg">Start Your Journey Today</button>
    </div>
   </div>
  </section><!-- About Section -->
  <section id="about" class="py-20 bg-gray-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 id="about-title" class="text-3xl md:text-4xl font-bold text-gray-800 mb-6">About Our Institute</h2>
     <p id="about-description" class="text-lg text-gray-600 max-w-3xl mx-auto">We are dedicated to providing high-quality computer education and digital skills training. Our experienced instructors and modern curriculum ensure students are well-prepared for the digital future.</p>
    </div>
    <div class="grid md:grid-cols-3 gap-8">
     <div class="bg-white p-8 rounded-lg shadow-lg card-hover fade-in text-center">
      <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
       <svg class="w-8 h-8 text-blue-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Expert Faculty</h3>
      <p class="text-gray-600">Learn from industry professionals with years of experience in computer education and technology.</p>
     </div>
     <div class="bg-white p-8 rounded-lg shadow-lg card-hover fade-in text-center">
      <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
       <svg class="w-8 h-8 text-green-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Practical Learning</h3>
      <p class="text-gray-600">Hands-on training with real-world projects to ensure you gain practical skills and experience.</p>
     </div>
     <div class="bg-white p-8 rounded-lg shadow-lg card-hover fade-in text-center">
      <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
       <svg class="w-8 h-8 text-purple-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.746 0 3.332.477 4.5 1.253v13C19.832 18.477 18.246 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Certification</h3>
      <p class="text-gray-600">Receive recognized certificates upon course completion to boost your career prospects.</p>
     </div>
    </div>
   </div>
  </section><!-- Courses Section -->
  <section id="courses" class="py-20 bg-white">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 id="courses-title" class="text-3xl md:text-4xl font-bold text-gray-800 mb-6">Our Courses</h2>
     <p class="text-lg text-gray-600 max-w-3xl mx-auto">Comprehensive computer courses designed to meet industry demands and student aspirations.</p>
    </div>
    <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
     <div class="bg-gradient-to-br from-blue-50 to-blue-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-blue-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 17V7m0 10a2 2 0 01-2 2H5a2 2 0 01-2-2V7a2 2 0 012-2h2a2 2 0 012 2m0 10a2 2 0 002 2h2a2 2 0 002-2M9 7a2 2 0 012-2h2a2 2 0 012 2m0 10V7m0 10a2 2 0 002 2h2a2 2 0 002-2V7a2 2 0 00-2-2h-2a2 2 0 00-2 2" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Basic Computer</h3>
      <p class="text-gray-600 mb-4">Learn fundamental computer skills including Windows, MS Office, and internet basics.</p>
      <div class="text-sm text-blue-600 font-medium">
       Duration: 3 months
      </div>
     </div>
     <div class="bg-gradient-to-br from-green-50 to-green-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-green-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Web Development</h3>
      <p class="text-gray-600 mb-4">Master HTML, CSS, JavaScript and create dynamic websites and web applications.</p>
      <div class="text-sm text-green-600 font-medium">
       Duration: 6 months
      </div>
     </div>
     <div class="bg-gradient-to-br from-purple-50 to-purple-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-purple-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10c0 2.21 3.582 4 8 4s8-1.79 8-4V7M4 7c0 2.21 3.582 4 8 4s8-1.79 8-4M4 7c0-2.21 3.582-4 8-4s8 1.79 8 4" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Database Management</h3>
      <p class="text-gray-600 mb-4">Learn SQL, database design, and management with hands-on practice.</p>
      <div class="text-sm text-purple-600 font-medium">
       Duration: 4 months
      </div>
     </div>
     <div class="bg-gradient-to-br from-red-50 to-red-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-red-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 4V2a1 1 0 011-1h8a1 1 0 011 1v2m-9 0h10m-10 0a2 2 0 00-2 2v14a2 2 0 002 2h10a2 2 0 002-2V6a2 2 0 00-2-2" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Digital Marketing</h3>
      <p class="text-gray-600 mb-4">Comprehensive digital marketing including SEO, social media, and online advertising.</p>
      <div class="text-sm text-red-600 font-medium">
       Duration: 5 months
      </div>
     </div>
     <div class="bg-gradient-to-br from-yellow-50 to-yellow-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-yellow-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2a2 2 0 002-2zm0 0V9a2 2 0 012-2h2a2 2 0 012 2v10m-6 0a2 2 0 002 2h2a2 2 0 002-2m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14a2 2 0 01-2 2h-2a2 2 0 01-2-2z" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Data Analysis</h3>
      <p class="text-gray-600 mb-4">Learn Excel advanced features, data visualization, and basic analytics.</p>
      <div class="text-sm text-yellow-600 font-medium">
       Duration: 4 months
      </div>
     </div>
     <div class="bg-gradient-to-br from-indigo-50 to-indigo-100 p-6 rounded-lg shadow-lg card-hover fade-in">
      <div class="w-12 h-12 bg-indigo-600 rounded-lg flex items-center justify-center mb-4">
       <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
       </svg>
      </div>
      <h3 class="text-xl font-semibold text-gray-800 mb-3">Cyber Security</h3>
      <p class="text-gray-600 mb-4">Essential cybersecurity concepts, network security, and ethical hacking basics.</p>
      <div class="text-sm text-indigo-600 font-medium">
       Duration: 6 months
      </div>
     </div>
    </div>
   </div>
  </section><!-- Contact Section -->
  <section id="contact" class="py-20 bg-gray-50">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="text-center mb-16 fade-in">
     <h2 id="contact-title" class="text-3xl md:text-4xl font-bold text-gray-800 mb-6">Get In Touch</h2>
     <p class="text-lg text-gray-600 max-w-3xl mx-auto">Ready to start your digital journey? Contact us today for more information about our courses and enrollment.</p>
    </div>
    <div class="grid md:grid-cols-2 gap-12">
     <div class="fade-in">
      <div class="bg-white p-8 rounded-lg shadow-lg">
       <h3 class="text-2xl font-semibold text-gray-800 mb-6">Contact Information</h3>
       <div class="space-y-4">
        <div class="flex items-center">
         <div class="w-10 h-10 bg-blue-100 rounded-full flex items-center justify-center mr-4">
          <svg class="w-5 h-5 text-blue-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
          </svg>
         </div>
         <div>
          <p class="text-sm text-gray-500">Phone</p>
          <p id="phone-display" class="text-gray-800 font-medium">+91 98765 43210</p>
         </div>
        </div>
        <div class="flex items-center">
         <div class="w-10 h-10 bg-green-100 rounded-full flex items-center justify-center mr-4">
          <svg class="w-5 h-5 text-green-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 4.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>
         </div>
         <div>
          <p class="text-sm text-gray-500">Email</p>
          <p id="email-display" class="text-gray-800 font-medium">info@chandandigital.com</p>
         </div>
        </div>
        <div class="flex items-center">
         <div class="w-10 h-10 bg-purple-100 rounded-full flex items-center justify-center mr-4">
          <svg class="w-5 h-5 text-purple-600" fill="none" stroke="currentColor" viewbox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z" /> <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
          </svg>
         </div>
         <div>
          <p class="text-sm text-gray-500">Address</p>
          <p id="address-display" class="text-gray-800 font-medium">123 Digital Street, Tech City, State 123456</p>
         </div>
        </div>
       </div>
      </div>
     </div>
     <div class="fade-in">
      <div class="bg-white p-8 rounded-lg shadow-lg">
       <h3 class="text-2xl font-semibold text-gray-800 mb-6">Send us a Message</h3>
       <form id="contact-form" class="space-y-4">
        <div><label for="name" class="block text-sm font-medium text-gray-700 mb-1">Full Name</label> <input type="text" id="name" name="name" required class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
        </div>
        <div><label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label> <input type="email" id="email" name="email" required class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
        </div>
        <div><label for="course" class="block text-sm font-medium text-gray-700 mb-1">Course Interest</label> <select id="course" name="course" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent"> <option value="">Select a course</option> <option value="basic-computer">Basic Computer</option> <option value="web-development">Web Development</option> <option value="database-management">Database Management</option> <option value="digital-marketing">Digital Marketing</option> <option value="data-analysis">Data Analysis</option> <option value="cyber-security">Cyber Security</option> </select>
        </div>
        <div><label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label> <textarea id="message" name="message" rows="4" class="w-full px-3 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent"></textarea>
        </div><button type="submit" class="w-full bg-blue-600 text-white py-3 px-4 rounded-md hover:bg-blue-700 transition-colors font-medium">Send Message</button>
       </form>
       <div id="form-message" class="mt-4 p-3 rounded-md hidden"></div>
      </div>
     </div>
    </div>
   </div>
  </section><!-- Footer -->
  <footer class="bg-gray-800 text-white py-12">
   <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
    <div class="grid md:grid-cols-3 gap-8">
     <div>
      <h3 id="footer-institute-name" class="text-xl font-bold mb-4">Chandan Digital Computer Institute</h3>
      <p class="text-gray-300 mb-4">Empowering students with digital skills for a brighter future. Join us and transform your career with comprehensive computer education.</p>
     </div>
     <div>
      <h4 class="text-lg font-semibold mb-4">Quick Links</h4>
      <ul class="space-y-2">
       <li><a href="#home" class="text-gray-300 hover:text-white transition-colors">Home</a></li>
       <li><a href="#about" class="text-gray-300 hover:text-white transition-colors">About</a></li>
       <li><a href="#courses" class="text-gray-300 hover:text-white transition-colors">Courses</a></li>
       <li><a href="#contact" class="text-gray-300 hover:text-white transition-colors">Contact</a></li>
      </ul>
     </div>
     <div>
      <h4 class="text-lg font-semibold mb-4">Contact Info</h4>
      <div class="space-y-2 text-gray-300">
       <p id="footer-phone">📞 +91 98765 43210</p>
       <p id="footer-email">✉️ info@chandandigital.com</p>
       <p id="footer-address">📍 123 Digital Street, Tech City</p>
      </div>
     </div>
    </div>
    <div class="border-t border-gray-700 mt-8 pt-8 text-center">
     <p class="text-gray-300">© 2024 Chandan Digital Computer Institute. All rights reserved.</p>
    </div>
   </div>
  </footer>
  <script>
        // Default configuration
        const defaultConfig = {
            institute_name: "Chandan Digital Computer Institute",
            tagline: "Empowering Students with Digital Excellence",
            hero_title: "Master Digital Skills for Tomorrow",
            hero_subtitle: "Join Chandan Digital Computer Institute and unlock your potential with comprehensive computer education and digital literacy programs",
            cta_button: "Start Your Journey Today",
            about_title: "About Our Institute",
            about_description: "We are dedicated to providing high-quality computer education and digital skills training. Our experienced instructors and modern curriculum ensure students are well-prepared for the digital future.",
            courses_title: "Our Courses",
            contact_title: "Get In Touch",
            phone_number: "+91 98765 43210",
            email_address: "info@chandandigital.com",
            address: "123 Digital Street, Tech City, State 123456"
        };

        // Mobile menu functionality
        document.getElementById('mobile-menu-btn').addEventListener('click', function() {
            const mobileMenu = document.getElementById('mobile-menu');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
                // Close mobile menu if open
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // Fade in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver(function(entries) {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        }, observerOptions);

        document.querySelectorAll('.fade-in').forEach(el => {
            observer.observe(el);
        });

        // Contact form handling
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            const formMessage = document.getElementById('form-message');
            formMessage.className = 'mt-4 p-3 rounded-md bg-green-100 text-green-700';
            formMessage.textContent = 'Thank you for your message! We will get back to you soon.';
            formMessage.classList.remove('hidden');
            
            // Reset form
            this.reset();
            
            // Hide message after 5 seconds
            setTimeout(() => {
                formMessage.classList.add('hidden');
            }, 5000);
        });

        // CTA button scroll to contact
        document.getElementById('cta-button').addEventListener('click', function() {
            document.getElementById('contact').scrollIntoView({
                behavior: 'smooth',
                block: 'start'
            });
        });

        // Element SDK configuration
        async function onConfigChange(config) {
            // Update navigation
            document.getElementById('nav-institute-name').textContent = config.institute_name || defaultConfig.institute_name;
            
            // Update hero section
            document.getElementById('hero-title').textContent = config.hero_title || defaultConfig.hero_title;
            document.getElementById('hero-subtitle').textContent = config.hero_subtitle || defaultConfig.hero_subtitle;
            document.getElementById('tagline').textContent = config.tagline || defaultConfig.tagline;
            document.getElementById('cta-button').textContent = config.cta_button || defaultConfig.cta_button;
            
            // Update about section
            document.getElementById('about-title').textContent = config.about_title || defaultConfig.about_title;
            document.getElementById('about-description').textContent = config.about_description || defaultConfig.about_description;
            
            // Update courses section
            document.getElementById('courses-title').textContent = config.courses_title || defaultConfig.courses_title;
            
            // Update contact section
            document.getElementById('contact-title').textContent = config.contact_title || defaultConfig.contact_title;
            document.getElementById('phone-display').textContent = config.phone_number || defaultConfig.phone_number;
            document.getElementById('email-display').textContent = config.email_address || defaultConfig.email_address;
            document.getElementById('address-display').textContent = config.address || defaultConfig.address;
            
            // Update footer
            document.getElementById('footer-institute-name').textContent = config.institute_name || defaultConfig.institute_name;
            document.getElementById('footer-phone').textContent = '📞 ' + (config.phone_number || defaultConfig.phone_number);
            document.getElementById('footer-email').textContent = '✉️ ' + (config.email_address || defaultConfig.email_address);
            document.getElementById('footer-address').textContent = '📍 ' + (config.address || defaultConfig.address);
        }

        function mapToCapabilities(config) {
            return {
                recolorables: [],
                borderables: [],
                fontEditable: undefined,
                fontSizeable: undefined
            };
        }

        function mapToEditPanelValues(config) {
            return new Map([
                ["institute_name", config.institute_name || defaultConfig.institute_name],
                ["tagline", config.tagline || defaultConfig.tagline],
                ["hero_title", config.hero_title || defaultConfig.hero_title],
                ["hero_subtitle", config.hero_subtitle || defaultConfig.hero_subtitle],
                ["cta_button", config.cta_button || defaultConfig.cta_button],
                ["about_title", config.about_title || defaultConfig.about_title],
                ["about_description", config.about_description || defaultConfig.about_description],
                ["courses_title", config.courses_title || defaultConfig.courses_title],
                ["contact_title", config.contact_title || defaultConfig.contact_title],
                ["phone_number", config.phone_number || defaultConfig.phone_number],
                ["email_address", config.email_address || defaultConfig.email_address],
                ["address", config.address || defaultConfig.address]
            ]);
        }

        // Initialize Element SDK
        if (window.elementSdk) {
            window.elementSdk.init({
                defaultConfig,
                onConfigChange,
                mapToCapabilities,
                mapToEditPanelValues
            });
        }
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'99693151924aa855',t:'MTc2MTgwOTI3My4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
