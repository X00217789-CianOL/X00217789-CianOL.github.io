
<!DOCTYPE html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Cian O'Loughlin</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-C6RzsynM9kWDrMNeT87bh95OGNyZPhcTNXj1NW7RuBCsyN/o0jlpcV8Qyq46cDfL" crossorigin="anonymous"></script>
    <!-- background colors -->
    <style>
        #hero-card{
            background-color:black;
        } 
        body{
            background-color: grey;
        }
        #footer{
            background-color: black;
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav id="navbar" class="navbar sticky-top navbar-dark bg-dark navbar-expand-md px-3">
        <a class="navbar-brand" href="#hero-card">Cian O'Loughlin</a>

        <!-- Hamburger Navbar -->
        <div class="navbar-collapse collapse" id="navbarToggleExternalContent">
            <div class="bg-dark p-4">
              <!-- Normal Navar -->
                <ul class="nav nav-pills">
                    <li class="nav-item">
                        <a class="nav-link" href="#bio">Bio</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#experience">Experience</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#education">Education</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#hobbies">Hobbies</a>
                    </li>
                    <li class="nav-item">
                        <a  class="nav-link" href="#footer" data-bs-toggle="modal" data-bs-target="#contactModal">Contact</a>
                    </li>
                </ul>
            </div>
        </div>
        <!-- Hamburger Navbar Button -->
        <nav class="navbar navbar-dark bg-dark navbar-expand-md px-3">
            <div class="container-fluid">
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
            </div>
        </nav>
    </nav>

    <!-- Scrollspy content (main body) -->
    <div data-bs-spy="scroll" data-bs-target="#navbar-example2" data-bs-root-margin="0px 0px -40%" data-bs-smooth-scroll="true" class="scrollspy-example bg-light" tabindex="0">

        <!-- Hero style banner -->
        <div id="hero-card" class="p-md-5 text-center">
            <div class="d-flex justify-content-center align-items-center h-100">
                <img src="images\Linkedin_Profile.png" class="rounded-circle" width="20%" >
                <div class="text-white">
                <h1 class="mb-3">Cian O'Loughlin</h1>
                <h4 class="mb-3">Computing with Machine Learning / AI</h4>
                </div>
            </div>
        </div>

        <!-- What kind of work / projects I am interested in -->
        <div id="bio" class="mx-auto col-md-10">
            <h2>Bio</h2>
            <p>I am a fourth year student in Technological University Dublin (TUD) Tallaght, studying Computing with Machine Learning / Artificial Intelligence. 
                I will be graduating in 2024 and will be looking for work in a data analytics role. I have an interest in the unearthing patterns within data that 
                can reveal insights that would go unnoticed otherwise. I also have a passion for all things technology, keeping my skills up to date by my participation 
                in many training courses and hackathons. Through my engagement with the community I have been exposed to a great deal of talented individuals and I hope 
                to further expand my netowork upon completion of my studies as I set out into industry.  
            </p>
        </div>

        <!-- Work Experience -->
        <div id="experience" class="mx-auto col-md-10">
            <h2>Experience</h2>

            <div id="experience-carousel" class="carousel carousel-dark slide text-center" data-bs-ride="true">
                <!-- Arrow buttons for the carousel -->
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#experience-carousel" data-bs-slide-to="0" class="active" aria-current="true" aria-label="intel-carousel-slide"></button>
                    <button type="button" data-bs-target="#experience-carousel" data-bs-slide-to="1" aria-label="CIS-carousel-slide"></button>
                </div>

                <!-- Carousel slides -->
                <div class="carousel-inner">

                    <!-- Slide 1: Intel Card -->
                    <div class="carousel-item active" id="intel">
                        <div class="card mx-auto">
                            <img src="images/Intel-logo.png" class="card-img-top h-50" style="max-height: 250px;" alt="Intel Logo">
                            <div class="card-body h-50">
                                <h3 class="card-title">Intel Corperation</h3>
                                <p class="card-text">
                                    As part of my course in TUS Limerick I was given the chance to partake in a work placement in Intel's reserach and development site in Shannon, Co.Clare.
                                    This was a 6 month placement from March 2023 - August 2023. During my time working here I was part of the Data Plane Development Kit (DPDK) power management team. 
                                    As part of this team I was reponsible for meeting daily/weekly goals set by my manager and team using agile methods to meet these goals. 
                                    Throughout my time working in Intel I was given the opurtunity to work with many teams and talents, however the main project I was working on was a customer facing demonstration
                                    for Kubernetes Power Manager. This involved working with a suite of technologies such as Docker, Kubernetes, Microk8s, Telegraf, Prometheus, and Grafana.     
                                </p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Slide 2: Camera Inspection Services Card -->
                    <div class="carousel-item" id="cis">
                        <div class="card mx-auto">
                            <img src="images/CIS-logo.png" class="card-img-top h-50" alt="Camera Inspection Services Logo">
                            <div class="card-body h-50">
                                <h3 class="card-title">Camera Inspection Services</h3>
                                <p class="card-text">
                                    During the time I took off before returning to education I worked in Camera Inspection Services (CIS).
                                    I started out as a Survey Technician, in this role I was responsible for recording the works that were taking place on site for quality purposes. 
                                    After a brief time in this role I was promoted to project manager. While in this role I was responsible for CIS's team on site, as well as communications with the customer and other opperators on site in order to achieve customer satisfaction.   
                                </p>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Carousel previous button -->
                <button class="carousel-control-prev" type="button" data-bs-target="#experience-carousel" data-bs-slide="prev">
                <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Previous</span>
                </button>

                <!-- Carousel next button -->
                <button class="carousel-control-next" type="button" data-bs-target="#experience-carousel" data-bs-slide="next">
                <span class="carousel-control-next-icon" aria-hidden="true"></span>
                <span class="visually-hidden">Next</span>
                </button>

            </div>
        </div>

        <!-- Education -->
        <div id="education" class="mx-auto col-md-10">
            <h2>Education</h2>
            <div class="accordion" id="education-accordion" style="background-color: lightgrey;">
                <!-- LIT -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseLIT" aria-expanded="true" aria-controls="collapseLIT">
                    <img src="images\TUS_Logo.png" width="10%"> Technological University of the Shannon
                    </button>
                    </h2>
                    <div id="collapseLIT" class="accordion-collapse collapse show" data-bs-parent="#accordionExample">
                        <div class="accordion-body">

                            <!-- Summary of LIT course. GPA, description, work placement, etc. -->
                            <strong>BSc Computing</strong>
                            <br>
                            <strong>GPA: 75.00%</strong>
                            <p>Description of Computing in LIT, frameworks learnt, languages, overall result</p>

                            <!-- LIT yearly breakdown tabs-->
                            <div class="card">
                                <div class="card-header">
                                    <ul class="nav nav-tabs card-header-tabs" data-bs-tabs="tabs">
                                        <li class="nav-item">
                                        <a class="nav-link active" aria-current="page" data-bs-toggle="tab" href="#year1">Year 1</a>
                                        </li>
                                        <li class="nav-item">
                                            <a class="nav-link" data-bs-toggle="tab" href="#year2">Year 2</a>
                                        </li>
                                        <li class="nav-item">
                                            <a class="nav-link" data-bs-toggle="tab" href="#year3">Year 3</a>
                                        </li>
                                    </ul>
                                </div>

                                <div class="card-body tab-content">
                                <!-- Year 1 Results -->
                                    <div class="tab-pane active" id="year1">
                                        <h2>Year 1</h2>

                                        <h5>Results</h5>
                                        <!-- GPA for Y1 -->
                                        <p><b>Stage GPA: 72.41</b></p>

                                        <!-- Results breakdown for semester 1 -->
                                        <div class="accordion" id="Semester1-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem1" aria-expanded="true" aria-controls="collapseSem1">
                                                        Semester 1
                                                    </button>
                                                </p>
                                                <div id="collapseSem1" class="accordion-collapse collapse show" data-bs-parent="#Semester1-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result %</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Web Development Fundamentals</td>
                                                                    <td>86</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Introduction to Programming</td>
                                                                    <td>85</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Interpersonal Skills</td>
                                                                    <td>82</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Computer Organisation and Architecture</td>
                                                                    <td>73</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Data Essentails</td>
                                                                    <td>66</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Computer Mathematics</td>
                                                                    <td>59</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <!-- Results breakdown for semester 2 -->
                                        <div class="accordion" id="Semester2-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem2" aria-expanded="false" aria-controls="collapseSem2">
                                                        Semester 2
                                                    </button>
                                                </p>
                                                <div id="collapseSem2" class="accordion-collapse collapse" data-bs-parent="#Semester2-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result %</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Introduction to Object Oriented Programming</td>
                                                                    <td>81</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Structured Programming</td>
                                                                    <td>79</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Responsive Design and Web Development</td>
                                                                    <td>74</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Mathematical Methods</td>
                                                                    <td>67</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Operating Systems Fundamentals</td>
                                                                    <td>63</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Structured Query Language Essentials</td>
                                                                    <td>54</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                    </div>

                                    <!-- Year 2 Results -->
                                    <div class="tab-pane" id="year2">
                                        <h2>Year 2</h2>

                                        <h5>Results</h5>

                                        <!-- GPA for Y21 -->
                                        <p><b>Stage GPA: 69.08%</b></p>

                                        <!-- Results breakdown for semester 3 -->
                                        <div class="accordion" id="Semester3-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem3" aria-expanded="true" aria-controls="collapseSem3">
                                                        Semester 3
                                                    </button>
                                                </p>
                                                <div id="collapseSem3" class="accordion-collapse collapse show" data-bs-parent="#Semester3-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result %</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Data Design and Programming</td>
                                                                    <td>84</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Software Development</td>
                                                                    <td>70</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Fundamentals of Data Structures and Algorithms</td>
                                                                    <td>68</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Object Oriented Theory and Programming</td>
                                                                    <td>67</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Discrete Mathematics</td>
                                                                    <td>66</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Networking Fundamentals</td>
                                                                    <td>58</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>


                                        <!-- Results breakdown for semester 4 -->
                                        <div class="accordion" id="Semester4-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem4" aria-expanded="false" aria-controls="collapseSem4">
                                                        Semester 4
                                                    </button>
                                                </p>
                                                <div id="collapseSem4" class="accordion-collapse collapse" data-bs-parent="#Semester4-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col">Module Name</th>
                                                                    <th scope="col">Result %</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Problem-Solving With Data Structures and Algorithms</td>
                                                                    <td>83</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Real Time Embedded Systems</td>
                                                                    <td>78</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Data Driven Systems</td>
                                                                    <td>65</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Applications Development</td>
                                                                    <td>65</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Internetworking</td>
                                                                    <td>64</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Software Testing</td>
                                                                    <td>61</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div id="year2Projects" class="m-3">
                                            <h5>Noteworthy projects</h5>
                                            <p><strong>Gym Management Application: </strong> 
                                            For the module Data Driven Systems I was tasked with creating a Create Read Update Delete (CRUD) 
                                            application that would showcase the skills I had practiced throughout the course of the module. 
                                            I chose to create an application that would assist in the managment of a Gym. This project was a web 
                                            based application that written in PHP that used AjaxAC, a PHP framework, to power the MVC application 
                                            and support queries to the database I designed to support the functionality that was implemented in the 
                                            front end of the application.  
                                            </p>
                                        </div>

                                    </div>

                                    <!-- Year 3 Results -->
                                    <div class="tab-pane" id="year3">
                                        
                                        <h2>Year 3</h2>

                                        <h5>Results</h5>
                                        <!-- GPA for Y3 -->
                                        <p><b>Stage GPA: 75.00%</b></p>

                                        <!-- Results breakdown for semester 5 -->
                                        <div class="accordion" id="Semester5-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem5" aria-expanded="true" aria-controls="collapseSem5">
                                                        Semester 5
                                                    </button>
                                                </p>
                                                <div id="collapseSem5" class="accordion-collapse collapse show" data-bs-parent="#Semester5-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result %</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Advanced Web Techniques</td>
                                                                    <td>84</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Computer Science</td>
                                                                    <td>82</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Concurrent Programming</td>
                                                                    <td>72</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Web Applications Architecture and Data Security</td>
                                                                    <td>70</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Software Engineering and Web Project</td>
                                                                    <td>67</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>


                                        <!-- Results breakdown for semester 6 -->
                                        <div class="accordion" id="Semester6-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem6" aria-expanded="false" aria-controls="collapseSem6">
                                                        Semester 6
                                                    </button>
                                                </p>
                                                <div id="collapseSem6" class="accordion-collapse collapse" data-bs-parent="#Semester6-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Pass/Fail</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Work Placement</td>
                                                                    <td>Pass</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                        <p>For more detail on tasks undertaken during the work placement module, see <a href=#intel>intel</a> in work experience section.</p>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div id="year3Projects" class="m-3">
                                            <h5>Noteworthy projects</h5>
                                            <p><strong>Farm Management Application: </strong> 
                                            For our group project module in third year we were put into a group of 4 and given a customer with whom we set up a weekly meeting. 
                                            The purpose of this meeting was to give us experience trying to draw specifications from a non technical client, as well as show the
                                            client our progress since our last meeting and gain any feedback or criticism the customer had for us. This was designed to give us 
                                            exposure to agile methodoligies before we went out to industry for our work placement module.</p><br> 

                                            <p>My teams customer tasked us with designing a web-based application in which he could manage his farm. The customer stressed that above 
                                            all else the documentation relating to the livestock on the farm was essential, as such we designed a system that allowed him to input 
                                            records of medicines, milk and beef yeilds, feed given, and various other fields relating to the livestock. The system also allowed the 
                                            customer to retrieve a specific animals records by scanning the NFC eartag that the animal has in their ear. Outside of livestock the finished 
                                            system allowed the customer to manage crop yeilds, fertilizer spread, projected fuel reserves and allowed the cutomer to see which animals were 
                                            in which field via an interactive map of the farms fields.</p><br> 
                                            
                                            <p>This application was designed using a mySQL database with stored procedures, we used PHP's CodeIgnitor framework to support our MVC framework and 
                                            created a responsive front end by encorperacting BootStrap 4 in the frontend. By making the application responsive we allowed the customer to use 
                                            the application on his mobile, making the application better suited to his needs on the farm. </p>
                                        </div>

                                    </div>
                                </div>
                            </div>  <!--card div-->
                        </div>
                    </div>
                </div>

                <!-- TUD -->
                <div class="accordion-item">
                    <h2 class="accordion-header">
                        <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTUD" aria-controls="collapseTUD">
                        <img src="images\TUD_Logo.png" width="10%"> Technological University Dublin
                        </button>
                    </h2>
                    <div id="collapseTUD" class="accordion-collapse collapse" data-bs-parent="#accordionExample">
                        <div class="accordion-body">
                            <strong>BSc (Hons) Computing with Machine Learning / AI</strong>
                            <br>
                            <strong>GPA: TBD</strong>
                            <p>Description of Computing in TUD, frameworks learnt, languages, overall result</p>

                            <!-- TUD yearly breakdown tabs-->
                            <div class="card">
                                <div class="card-header">
                                    <ul class="nav nav-tabs card-header-tabs" data-bs-tabs="tabs">
                                        <li class="nav-item">
                                        <a class="nav-link active" aria-current="page" data-bs-toggle="tab" href="#year4">Year 4</a>
                                        </li>
                                    </ul>
                                </div>

                                <!-- Year 4 Results -->
                                <div class="card-body tab-content">
                                    <div class="tab-pane active" id="year1">
                                        <h2>Year 4</h2>

                                        <h5>Results</h5>
                                        <!-- GPA for Y4 -->
                                        <p><b>Stage GPA: TBD</b></p>

                                        <!-- Results breakdown for semester 7 -->
                                        <div class="accordion" id="Semester7-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem7" aria-expanded="true" aria-controls="collapseSem7">
                                                        Semester 7
                                                    </button>
                                                </p>
                                                <div id="collapseSem7" class="accordion-collapse collapse show" data-bs-parent="#Semester7-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Aplied Machine Learning</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>DevOps</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Interactive Media and Design</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Social Media Analysis</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Information Management</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Final Year Project (Part 1)</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <!-- Results breakdown for semester 8 -->
                                        <div class="accordion" id="Semester8-accordian">
                                            <div class="accordion-item">
                                                <p class="accordion-header">
                                                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseSem8" aria-expanded="false" aria-controls="collapseSem8">
                                                        Semester 8
                                                    </button>
                                                </p>
                                                <div id="collapseSem8" class="accordion-collapse collapse" data-bs-parent="#Semester8-accordion">
                                                    <div class="accordion-body">
                                                        <table class="table">
                                                            <thead>
                                                                <tr>
                                                                    <th scope="col-9">Module Name</th>
                                                                    <th scope="col-3">Result</th>
                                                                </tr>
                                                            </thead>
                                                            <tbody>
                                                                <tr>
                                                                    <td>Applied Artificial Intelligence and Deep Learning</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Data Analysis and Programming</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>E-Learning Elective</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>IT Governance and Quality</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                                <tr>
                                                                    <td>Final Year Project (Part 2)</td>
                                                                    <td>TBD</td>
                                                                </tr>
                                                            </tbody>
                                                        </table>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>

                                        <div id="year4projects" class="m-3">
                                            <h5>Noteworthy Projects</h5>
                                            <strong>Fire Detection Using Computer Vision</strong>
                                            <p>For my final year project I has chosen to design an algorithm that will effectively detect fire in CCTV footage.
                                                In order to achieve this I have researched similar projects to examine existing solutions and see how they can be improved upon. 
                                                Since completing thsi I have began the collecting a suitable dataset on which to train and test this algorithm. So far I have collected
                                                21,000 images from various datasets from many sources. Once I have completed collecting the data I will begin data pre-processing which 
                                                will have me making the dataset uniform. I expect the main challenge I will face in this stepp will be scaling of the images. As the images
                                                are collected from various sources they are various different sizes, I will need to change the size of the images to 200 x 200 pixels so as 
                                                the CNN can process this. From here I will be training and testing multiple models to evaluate their performance before ultimately chosing a
                                                model for the final project. 
                                            </p>
                                        </div>
                                    </div>
                                </div>
                            </div>  <!--card div-->
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Hobbies / Interests -->
        <div id="hobbies" class="mx-auto col-md-10">
            <h2>Interests</h2>
            <strong>Gaelic Football</strong>
            <p>In my early childhood years I was introduced to Gaelic football and ever since I have been hooked. I play for my local team, Ellistown GAA.
                This is a small club in Kildare with around 300 members. As such the sense of community here is fantastic. I have played almost all age groups throughout 
                my years with the club and have enjoyed working as part of the team throughout my time here. 
            </p><br>    
            <strong>Powerlifting</strong>
            <p>In more recent years I was introduced to weightliftning as a means to increase performance on the GAA pitch, however I thoroughly enjoyed the weight 
                training section of our pre-season training and found myself a new hobby in powerlifting. Although I am yet to compete in a powerliftng competition 
                I am currently training for a competition in July 2024 where I hope to get to know the community in Irish Powerlifting better. 
            </p><br>    
            <strong></strong>
            <p></p>    
        </div>

        <!-- Modal -->
        <div class="modal fade" id="contactModal" tabindex="-1" aria-labelledby="modalLabel" aria-hidden="true">
            <div class="modal-dialog modal-xl">
                <div class="modal-content">
                    <!-- Modal Header -->
                    <div class="modal-header">
                        <h1 class="modal-title fs-5" id="modalLabel">Get in touch</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                        <div class="row">
                            <div class="col-md-6">
                                <strong>My Details:</strong>
                                <div class="container">
                                    <!-- Javascript functions to copy items to clipboard -->
                                    <script>
                                        function copyMyEmail() {
                                            // Get the text field
                                            var copyText = document.getElementById("myEmail");
                                            copyText.select();
                                            copyText.setSelectionRange(0, 99999); // For mobile devices
                                             // Copy the text to clipboard
                                            navigator.clipboard.writeText(copyText.value);
                                            // Alert the copied text
                                            alert("Copied the text: " + copyText.value);
                                          }
                                        function copyMobileNumber() {
                                            var copyText = document.getElementById("myNumber");
                                            copyText.select();
                                            copyText.setSelectionRange(0, 99999); 
                                            navigator.clipboard.writeText(copyText.value);
                                            alert("Copied the text: " + copyText.value);
                                          }
                                        function copyLinkedinLink() {
                                            var copyText = document.getElementById("myLinkedin");
                                            copyText.select();
                                            copyText.setSelectionRange(0, 99999);
                                            navigator.clipboard.writeText(copyText.value);
                                            alert("Copied the text: " + copyText.value);
                                          }
                                    </script>
                                    <div class="row mb-3">
                                        <label for="myEmail" class="form-label">Email</label>
                                        <div class="row">
                                            <div class="col-8">
                                                <input type="text" class="form-control" id="myEmail" value="cianoloughlin01@gmail.com" disabled>
                                            </div>
                                            <div class="col-4">
                                                <button onclick="copyMyEmail()"><img src="images/copy-icon.png" class="col-4"></button>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row mb-3">
                                        <label for="myNumber" class="form-label">Mobile Number</label>
                                        <div class="row">
                                            <div class="col-8">
                                            <input type="mobile" class="form-control" id="myNumber" value="0894791376" disabled>
                                            </div>
                                            <div class="col-4">
                                            <button onclick="copyMobileNumber()"><img src="images/copy-icon.png" class="col-4"></button>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row mb-3">
                                        <label for="myLinkedin" class="form-label">LinkedIn</label>
                                        <div class="row">
                                            <div class="col-8">
                                            <input type="text" class="form-control" id="myLinkedin" value="https::/www.linkedin.com/in/cian-o-loughlin-41060220b" disabled>
                                            </div>
                                            <div class="col-4">
                                            <button onclick="copyLinkedinLink()"><img src="images/copy-icon.png" class="col-4"></button>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="col-md-6">
                                <strong>Leave a message:</strong>
                                <form>
                                    <div class="mb-3">
                                        <label for="InputEmail" class="form-label" aria-placeholder="example@email.com">Your Email</label>
                                        <input type="email"  class="form-control" id="inputEmail">
                                    </div>
                                    <div class="mb-3">
                                        <label for="inputMessage" class="form-label">Message</label>
                                        <input type="text" class="form-control" id="inputMessage">
                                    </div>
                                    <div class="mb-3 d-flex justify-content-center align-items-center">
                                        <button type="submit" class="btn btn-primary m-1" data-bs-dismiss="modal">Submit</button>
                                        <button type="button" class="btn btn-secondary m-1" data-bs-dismiss="modal">Close</button>
                                    </div>
                                </form>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    

        <!-- Contact info / footer -->
        <footer id="footer">
            
            <!-- Div to contain the footer columns -->
            <div class="row text-center">
                <!-- LinkedIn link and photo -->
                <div id="footer-socials" class="col-4">
                    <a class="text-white" href="https://www.linkedin.com/in/cian-o-loughlin-41060220b"><img src="images/linkedin-icon.png" alt="LinkedIn Icon" class="col-2">LinkedIn</a>    
                </div>

                <!-- Phone Number -->
                <div id="footer-blank" class="col-4">
                </div>

                <!-- Email -->
                <div id="footer-email" class="col-4">
                    <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#contactModal">
                        Contact Me 
                    </button>
                </div>
            </div>
        </footer>
    </div>

</body>
