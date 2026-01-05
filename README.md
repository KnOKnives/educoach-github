
--------------------------------------------------
1.  index.html  (root)
------------------------------------------------```html
<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>EduCoach – Premium Online Coaching</title>
    <!-- CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <link href="assets/css/style.css" rel="stylesheet">
</head>
<body>
<!-- ============  NAVBAR  ============ -->
<nav class="navbar navbar-expand-lg navbar-dark fixed-top" id="mainNav">
    <div class="container">
        <a class="navbar-brand" href="#home"><i class="fas fa-graduation-cap me-2"></i>EduCoach</a>
        <button class="navbar-toggler" data-bs-toggle="collapse" data-bs-target="#navbarNav">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav ms-auto align-items-lg-center">
                <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#classes">Classes</a></li>
                <li class="nav-item"><a class="nav-link" href="#routine">Routine</a></li>
                <li class="nav-item"><a class="nav-link" href="#live">Live</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                <li class="nav-item ms-lg-3">
                    <button class="btn btn-light btn-sm" data-bs-toggle="modal" data-bs-target="#loginModal">Login</button>
                </li>
                <li class="nav-item ms-lg-3">
                    <button class="theme-toggle" id="themeToggle" title="Toggle dark mode"><i class="fas fa-moon"></i></button>
                </li>
            </ul>
        </div>
    </div>
</nav>

<!-- ============  HERO  ============ -->
<section id="home" class="hero-section">
    <div class="container hero-content">
        <div class="row align-items-center">
            <div class="col-lg-6">
                <h1 class="display-4 fw-bold mb-4">Transform Your Learning Journey</h1>
                <p class="lead mb-4">Join thousands of students in our premium online coaching platform. Experience world-class education with expert teachers, live classes, and personalized learning paths.</p>
                <div class="d-flex gap-3 flex-wrap">
                    <button class="btn btn-light btn-lg px-4" data-bs-toggle="modal" data-bs-target="#loginModal"><i class="fas fa-rocket me-2"></i>Start Learning Today</button>
                    <a href="#classes" class="btn btn-outline-light btn-lg px-4"><i class="fas fa-play me-2"></i>Watch Demo</a>
                </div>
            </div>
            <div class="col-lg-6 text-center"><i class="fas fa-chalkboard-teacher" style="font-size:14rem;opacity:.85"></i></div>
        </div>
    </div>
</section>

<!-- ============  STATS  ============ -->
<section class="stats-section py-5">
    <div class="container">
        <div class="row text-center">
            <div class="col-md-3 col-6"><div class="stat-card"><span class="stat-number">10K+</span><p class="mb-0">Active Students</p></div></div>
            <div class="col-md-3 col-6"><div class="stat-card"><span class="stat-number">500+</span><p class="mb-0">Expert Teachers</p></div></div>
            <div class="col-md-3 col-6"><div class="stat-card"><span class="stat-number">1000+</span><p class="mb-0">Live Classes</p></div></div>
            <div class="col-md-3 col-6"><div class="stat-card"><span class="stat-number">95%</span><p class="mb-0">Success Rate</p></div></div>
        </div>
    </div>
</section>

<!-- ============  FEATURES  ============ -->
<section id="classes" class="py-5">
    <div class="container">
        <div class="text-center mb-5"><h2 class="display-5 fw-bold">Why Choose EduCoach?</h2><p class="lead text-muted">Discover the features that make us the preferred choice for online learning</p></div>
        <div class="row g-4">
            <div class="col-md-4"><div class="card h-100 text-center p-4"><div class="feature-icon mx-auto mb-3"><i class="fas fa-video fa-2x"></i></div><h4>Live Interactive Classes</h4><p>Join real-time classes with expert teachers. Ask questions, participate in discussions, and learn collaboratively.</p></div></div>
            <div class="col-md-4"><div class="card h-100 text-center p-4"><div class="feature-icon mx-auto mb-3"><i class="fas fa-calendar-alt fa-2x"></i></div><h4>Flexible Scheduling</h4><p>Access classes according to your routine. Never miss a lesson with our comprehensive scheduling system.</p></div></div>
            <div class="col-md-4"><div class="card h-100 text-center p-4"><div class="feature-icon mx-auto mb-3"><i class="fas fa-user-graduate fa-2x"></i></div><h4>Personalized Learning</h4><p>Get customized learning paths based on your goals, pace, and performance. Track your progress effectively.</p></div></div>
        </div>
    </div>
</section>

<!-- ============  LIVE CLASSES  ============ -->
<section id="live" class="py-5 bg-light">
    <div class="container">
        <div class="text-center mb-5"><h2 class="display-5 fw-bold">Today's Live Classes</h2><p class="lead text-muted">Join our interactive live sessions</p></div>
        <div class="row g-4">
            <div class="col-lg-6">
                <div class="class-card h-100">
                    <div class="d-flex justify-content-between align-items-start mb-3">
                        <div><h5 class="mb-1">Advanced Mathematics</h5><p class="text-muted mb-0">Calculus – Integration Techniques</p></div>
                        <span class="class-time">10:00 AM</span>
                    </div>
                    <div class="d-flex align-items-center justify-content-between">
                        <div class="d-flex align-items-center">
                            <img src="https://via.placeholder.com/50" alt="Teacher" class="teacher-avatar me-3">
                            <div><h6 class="mb-0">Dr. Sarah Johnson</h6><small class="text-muted">Mathematics Expert</small></div>
                        </div>
                        <div class="text-end">
                            <span class="badge bg-success px-3 py-2"><span class="live-indicator"></span> LIVE</span>
                            <div class="mt-2"><a href="https://us05web.zoom.us/j/123456789" target="_blank" class="zoom-link"><i class="fas fa-video me-1"></i>Join Zoom</a></div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6">
                <div class="class-card h-100">
                    <div class="d-flex justify-content-between align-items-start mb-3">
                        <div><h5 class="mb-1">Physics Fundamentals</h5><p class="text-muted mb-0">Mechanics – Newton's Laws</p></div>
                        <span class="class-time">2:00 PM</span>
                    </div>
                    <div class="d-flex align-items-center justify-content-between">
                        <div class="d-flex align-items-center">
                            <img src="https://via.placeholder.com/50" alt="Teacher" class="teacher-avatar me-3">
                            <div><h6 class="mb-0">Prof. Michael Chen</h6><small class="text-muted">Physics Expert</small></div>
                        </div>
                        <div class="text-end">
                            <span class="badge bg-warning text-dark px-3 py-2">UPCOMING</span>
                            <div class="mt-2"><small class="text-muted">Starts in 2 hours</small></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- ============  ROUTINE  ============ -->
<section id="routine" class="py-5">
    <div class="container">
        <div class="text-center mb-5"><h2 class="display-5 fw-bold">Weekly Routine</h2><p class="lead text-muted">Your complete class schedule</p></div>
        <div class="table-responsive routine-table">
            <table class="table mb-0">
                <thead><tr><th>Time</th><th>Monday</th><th>Tuesday</th><th>Wednesday</th><th>Thursday</th><th>Friday</th><th>Saturday</th></tr></thead>
                <tbody>
                    <tr>
                        <td><strong>9:00 AM</strong></td>
                        <td><div class="text-primary fw-bold">Mathematics</div><small class="text-muted">Room 101</small></td>
                        <td><div class="text-success fw-bold">Physics</div><small class="text-muted">Lab 201</small></td>
                        <td><div class="text-primary fw-bold">Mathematics</div><small class="text-muted">Room 101</small></td>
                        <td><div class="text-success fw-bold">Physics</div><small class="text-muted">Lab 201</small></td>
                        <td><div class="text-warning fw-bold">Chemistry</div><small class="text-muted">Lab 301</small></td>
                        <td>-</td>
                    </tr>
                    <tr>
                        <td><strong>11:00 AM</strong></td>
                        <td><div class="text-info fw-bold">English</div><small class="text-muted">Room 102</small></td>
                        <td><div class="text-danger fw-bold">Biology</div><small class="text-muted">Lab 202</small></td>
                        <td><div class="text-info fw-bold">English</div><small class="text-muted">Room 102</small></td>
                        <td><div class="text-warning fw-bold">Chemistry</div><small class="text-muted">Lab 301</small></td>
                        <td><div class="text-secondary fw-bold">Computer Sci.</div><small class="text-muted">Lab 401</small></td>
                        <td><div class="text-dark fw-bold">Mock Test</div><small class="text-muted">Hall A</small></td>
                    </tr>
                    <tr>
                        <td><strong>2:00 PM</strong></td>
                        <td>-</td>
                        <td><div class="text-success fw-bold">Physics</div><small class="text-muted">Lab 201</small></td>
                        <td><div class="text-warning fw-bold">Chemistry</div><small class="text-muted">Lab 301</small></td>
                        <td>-</td>
                        <td><div class="text-primary fw-bold">Maths Quiz</div><small class="text-muted">Room 105</small></td>
                        <td>-</td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</section>

<!-- ============  FOOTER  ============ -->
<footer class="footer py-5">
    <div class="container text-center">
        <h5 class="mb-3">EduCoach – Empowering Learners Worldwide</h5>
        <p class="mb-0">&copy; <span id="yr"></span> EduCoach. All rights reserved.</p>
    </div>
</footer>

<!-- ============  LOGIN MODAL  ============ -->
<div class="modal fade" id="loginModal" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog modal-dialog-centered">
        <div class="modal-content">
            <div class="login-header">
                <h4 class="mb-0"><i class="fas fa-key me-2"></i><span id="modalTitle">Welcome Back</span></h4>
            </div>
            <div class="p-4">
                <div class="btn-group w-100 mb-3" role="group">
                    <input type="radio" class="btn-check" name="userType" id="userTab" checked>
                    <label class="btn btn-outline-primary" for="userTab" onclick="switchMode('user')">Student / Teacher</label>
                    <input type="radio" class="btn-check" name="userType" id="adminTab">
                    <label class="btn btn-outline-danger" for="adminTab" onclick="switchMode('admin')">Admin</label>
                </div>

                <form id="userForm" onsubmit="userLogin(event)">
                    <div class="mb-3"><label class="form-label">Email</label><input type="email" class="form-control" placeholder="you@example.com" required></div>
                    <div class="mb-3"><label class="form-label">Password</label><input type="password" class="form-control" placeholder="••••••••" required></div>
                    <div class="d-grid"><button class="btn btn-primary">Login</button></div>
                </form>

                <form id="adminForm" class="d-none" onsubmit="adminLogin(event)">
                    <div class="mb-3"><label class="form-label">Admin Username</label>
                        <select class="form-select" id="adminUser" required>
                            <option value="" disabled selected>Select admin</option>
                            <option>admin1</option><option>admin2</option><option>admin3</option>
                        </select>
                    </div>
                    <div class="mb-3"><label class="form-label">11-digit Password</label><input type="password" id="adminPin" class="form-control" placeholder="12345678901" maxlength="11" required></div>
                    <div class="d-grid"><button class="btn btn-danger">Admin Login</button></div>
                </form>
            </div>
        </div>
    </div>
</div>

<!-- ============  ADMIN DASH MODAL  ============ -->
<div class="modal fade" id="adminModal" tabindex="-1" aria-hidden="true">
    <div class="modal-dialog modal-lg modal-dialog-centered">
        <div class="modal-content">
            <div class="modal-header bg-danger text-white">
                <h5 class="modal-title"><i class="fas fa-shield-alt me-2"></i>Admin Dashboard</h5>
                <button type="button" class="btn-close btn-close-white" data-bs-dismiss="modal"></button>
            </div>
            <div class="modal-body">
                <p>Welcome <strong id="adminName"></strong>!</p>
                <div class="row g-4 text-center">
                    <div class="col-md-4"><div class="card p-3"><div class="stat-number">10K+</div><p>Active Students</p></div></div>
                    <div class="col-md-4"><div class="card p-3"><div class="stat-number">500+</div><p>Teachers</p></div></div>
                    <div class="col-md-4"><div class="card p-3"><div class="stat-number">95%</div><p>Success Rate</p></div></div>
                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
            </div>
        </div>
    </div>
</div>

<!-- ============  JS  ============ -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/bcryptjs@2.4.3/dist/bcrypt.min.js"></script>
<script src="assets/js/main.js"></script>
</body>
</html>
