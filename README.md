# cs200p1
project 1 repository for my group members and I to use

﻿<!DOCTYPE html>

<html lang="en" xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, intial-scale=1.0" />
    <title>Report.html</title>
    <style>
        body {
            font-family: Cambria, Cochin, Georgia, Times, Times New Roman, serif;
            margin: 20px;
            background-color: #f9f9f9;
        }

        table {
            width: 100%;
            margin-top: 20px;
        }

        table, th, td {
            border: 0.5px solid rgb(255, 0, 81);
        }

        th, td {
            border: 0.5px solid rgb(255, 0, 81);
            padding: 10px;
            text-align: center;
        }

        th {
            background-color: #ab0000;
            color: white;
        }

        tr:hover {
            background-color: #f1f1f1;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

            nav ul li {
                position: relative;
                display: inline-block;
            }

        nav a {
            color: black;
            text-decoration: none;
            padding: 10px 15px;
            display: block;
        }

        nav .dropdown-content {
            display: none; /* Hide dropdown content initially */
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            z-index: 1;
        }

            nav .dropdown-content a {
                color: black;
                padding: 12px 16px;
                text-decoration: none;
                display: block;
            }

        nav ul li:hover .dropdown-content {
            display: block; /* Show dropdown on hover */
        }

        nav ul li:hover > a {
            background-color: #575757; /* Change background on hover */
        }

        #glossary {
            height: 1390px;
        }

        #useCaseDiagram {
            height: 800px;
        }

        section {
            padding: 20px;
            border: 1px solid #ddd;
            margin: 10px 0;
            height: 300px; /* Make sections tall for scrolling */
        }

        /* Back to Top Button */
        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #ab0000;
            color: white;
            border: none;
            padding: 10px 15px;
            cursor: pointer;
            display: none; /* Hidden by default */
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.3);
        }

        /* Show button when scrolling down */
        window.onscroll = function() {
            const button = document.querySelector('.back-to-top');
            if (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200)

        {
            button .style.display = 'block';
        }

        else {
            button .style.display = 'none';
        }
        }
    </style>
</head>

<body>
    <header>
        <h1>CS 200 Team 3 - Project 1</h1> <!--Title of the page-->
        <nav>
            <ul class="dropdown">
                <!--Creates a class for a dropdown menu-->
                <li>
                    <a href="#">Menu</a> <!--All content listed in dropdown menu-->
                    <ul class="dropdown-content">
                        <li><a href="#team">Team Members</a></li>
                        <li><a href="#taskTable">Task Distribution Table</a></li>
                        <li><a href="#summary">Summary</a></li>
                        <li><a href="#glossary">Glossary</a></li>
                        <li><a href="#useCaseDescription">Use Case Description</a></li>
                        <li><a href="#useCaseDiagram">Use Case Diagram</a></li>
                    </ul>
                </li>
            </ul>
        </nav>
    </header>

    <section id="team">
        <!--Section 1 - drop menu-->
        <h3>Team</h3>
        <table>
            <tbody>
                <!--Table of all team members -->
                <tr>
                    <td>Drew Estill</td>
                    <td>12205884</td>
                    <td>amestill@crimson.ua.edu</td>
                    <td>10 hours 45 minutes</td>
                </tr>
                <tr>
                    <td>Nuzhat Noeri</td>
                    <td>12326186</td>
                    <td>nnoeri@crimson.ua.edu</td>
                    <td>8 hours 5 minutes </td>
                </tr>
                <tr>
                    <td>Cody Caulfield</td>
                    <td>12447052</td>
                    <td>crcaulfield@crimson.ua.edu</td>
                    <td>6 hours 17 minutues </td>
                </tr>
                <tr>
                    <td>Darralynn Joiner (submitter)</td>
                    <td>11958020</td>
                    <td>dejoiner@crimson.ua.edu</td>
                    <td>7 hours 12 minutes </td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="taskTable">
        <!--Section 2 - drop down menu-->
        <h3> Task Distribution Table </h3>
        <table>
            <thead>
                <!--Header table-->
                <tr>
                    <th>Name</th>
                    <th>Task</th>
                    <th>Percent Complete</th>
                </tr>
            </thead>
            <tbody>
                <!--Indivual cells listed under header table-->
                <tr>
                    <td>Drew Estill</td>
                    <td>Use Case Diagram, Use Case Descriptions</td>
                    <td>25%</td>
                </tr>
                <tr>
                    <td>Nuhat Noeri</td>
                    <td>Use Case Diagram, Glossary</td>
                    <td>25%</td>
                </tr>
                <tr>
                    <td>Cody Caulfield</td>
                    <td>Use Case Diagram, Use Case Descriptions</td>
                    <td>25%</td>
                </tr>
                <tr>
                    <td>Darralynn Joiner</td>
                    <td>Use Case Diagram, Summary</td>
                    <td>25%</td>
                </tr>
            </tbody>
        </table>
    </section>

    <section id="summary">
        <!--Section 3 - drop down menu-->
        <h3>Summary</h3>
    </section>

    <section id="glossary">
        <!--Section 4 - drop down menu-->
        <body>
            <h2>Glossary</h2>

            <table>
                <tr>
                    <th>Term</th>
                    <th>Description</th>

                </tr>
                <tr>
                    <td>Member</td>
                    <td>
                        -individual subscribed to ChocAn<br> -pays monthly subscription<br> -receives services from Providers<br> -has a plastic membership card
                    </td>

                </tr>
                <tr>
                    <td>Membership Card</td>
                    <td>-plastic<br> -name of member<br> -9 digit member identification number</td>

                </tr>
                <tr>
                    <td>Member Identification Number</td>
                    <td>-9 digits<br> -Provider inputs this in terminal to check status<br> -valid/invalid/suspended</td>

                </tr>
                <tr>
                    <td>Provider</td>
                    <td>-healthcare professional who offers services to ChocAn<br> -inputs member identification number into a terminal to check member validation<br> -inputs a 6-digit service code into terminal for ChocAn Data Center to issue bill</td>

                </tr>
                <tr>
                    <td>
                        Provider Number<t /d>
                            <td>-9 digits<br> -given to each ChocAn provider and stored in the ChocAn Data Center</td>
                </tr>
                <tr>
                    <td>Service Code</td>
                    <td>-6 digits<br> -specific healthcare service<br> -found in the Provider Directory<br> Providers input thid code into terminal to issue bill</td>
                </tr>
                <tr>
                    <td>Provider Directory</td>
                    <td>-a list of service codes, service names, and service fees</td>
                </tr>
                <tr>
                    <td>ChocAn Data Center</td>
                    <td>-central system<br> -contains member, provider, service codes and details<br> -validates member status<br> -generates weekly reports<br> -generates EFT</td>
                </tr>
                <tr>
                    <td>Terminal</td>
                    <td>-used by Providers to input member identification code and service code<br> -output error message if not valid or suspended</td>
                </tr>
                <tr>
                    <td>Validity</td>
                    <td>-member identification code needs to be checked for validity for Providers to give service<br> -invalid if wrong/non-existing within ChocAn Data Center<br> -suspended if one month's subscription is not paid<br> -account will be reinstated after subscription is paid</td>
                </tr>
                <tr>
                    <td>Weekly Report</td>
                    <td>-generated by ChocAn Data Center<br> -members receive member report<br> -Providers receive provider report<br> -an EFT is generated</td>
                </tr>
                <tr>
                    <td>Member Report</td>
                    <td>-generated weekly<br> -includes services received, serice date, and Provider name</td>
                </tr>
                <tr>
                    <td>Provider Report</td>
                    <td>-generated weekly<br> -includes services provided, dates, service codes, fees</td>
                </tr>
                <tr>
                    <td>EFT</td>
                    <td>-a file containing details of provider payments<br> -provider name, provider number, amount to be paid<br> -sent to Banking service </td>
                </tr>
                <tr>
                    <td>Acme Accounting Service</td>
                    <td>-third party organisation<br> -handles ChocAn membership fee payment<br> -suspends member accounts if monthly fee is not paid<br> -reinstates after monthly fee is paid</td>
                </tr>
                <tr>
                    <td>Banking Service</td>
                    <td>-ChocAn Data Center sends the weekly generated EFT to process the payment to Providers</td>
                </tr>
            </table>

        </body>


    </section>

    <section id="useCaseDescription">
        <!--Section 5 - drop down menu-->
        <h3>Use Case Description</h3>
    </section>

    <section id="useCaseDiagram">
        <!--Section 6 - drop down menu-->
        <h3>Use Case Diagram</h3>
        <img src="use.png" width="1400" height="750" /> <!--Image source for the file-->
    </section>

    <!--Button Operations-->
    <!--Creates a class and class function for a "Back to Top button"-->
    <button class="back-to-top" onclick="scrollToTop()">Back to Top</button>


    <script>
        function scrollToTop() {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        window.onscroll = function() {
            const button = document.querySelector('.back-to-top');
            if (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) {
                button.style.display = "block";
            }
            else {
                button.style.display = 'none';
            }
        };
    </script>
</body>
</html>
