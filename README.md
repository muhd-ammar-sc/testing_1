[test1.html](https://github.com/user-attachments/files/33083007/test1.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=yes">
    <title>Class Timetable | Simple & Clean</title>
    <style>

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background: #f4f7fc;   
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', sans-serif;
            padding: 2rem 1.5rem;
            color: #1a2c3e;
        }


        .container {
            max-width: 1300px;
            margin: 0 auto;
            background: white;
            border-radius: 28px;
            box-shadow: 0 12px 28px rgba(0, 0, 0, 0.05), 0 2px 4px rgba(0, 0, 0, 0.02);
            padding: 1.8rem 1.5rem 2.2rem 1.5rem;
            transition: all 0.2s;
        }

        .section-title {
            font-size: 1.7rem;
            font-weight: 600;
            letter-spacing: -0.3px;
            margin: 0 0 0.35rem 0;
            color: #0b3954;
            display: inline-block;
            border-left: 5px solid #2b7a62;
            padding-left: 1rem;
        }

        .subhead {
            color: #4a627a;
            margin-bottom: 1.8rem;
            font-size: 0.95rem;
            border-bottom: 1px solid #e2edf2;
            padding-bottom: 0.6rem;
        }

        .timetable-wrapper {
            overflow-x: auto;
            margin-bottom: 2.5rem;
            border-radius: 20px;
            border: 1px solid #e2edf2;
            background: #fff;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.9rem;
            min-width: 700px;
        }

        th, td {
            padding: 14px 12px;
            text-align: left;
            vertical-align: middle;
            border-bottom: 1px solid #e9edf2;
            border-right: none;
            border-left: none;
        }

        th {
            background-color: #f0f6fa;
            font-weight: 600;
            color: #1e4a6e;
            font-size: 0.85rem;
            letter-spacing: 0.3px;
            text-transform: uppercase;
            border-bottom: 2px solid #cfdfe8;
        }

        td {
            background-color: #ffffff;
            color: #1f2f3e;
        }

        td:first-child, th:first-child {
            background-color: #fafcfe;
            font-weight: 500;
            color: #0f4c5f;
            width: 115px;
        }

        tr:hover td {
            background-color: #fefdf7;
        }

        .emoji {
            font-size: 1.05rem;
            display: inline-block;
            margin-right: 4px;
        }

        .course-code {
            font-weight: 600;
            color: #1f6392;
        }

        .badge {
            display: inline-block;
            background: #eef2f5;
            font-size: 0.7rem;
            font-weight: 500;
            padding: 2px 8px;
            border-radius: 30px;
            color: #2c5a74;
            margin-left: 6px;
            letter-spacing: 0.2px;
        }

        .break-symbol {
            font-weight: 700;
            font-size: 1.2rem;
            color: #2b7a62;
            letter-spacing: 1px;
        }

        .instructor-grid {
            overflow-x: auto;
            margin-top: 0.5rem;
        }

        .instructor-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.85rem;
            background: white;
            border-radius: 20px;
        }

        .instructor-table th {
            background: #e9f2f0;
            color: #165a44;
            font-weight: 600;
            text-transform: none;
            font-size: 0.85rem;
            padding: 12px 10px;
        }

        .instructor-table td {
            padding: 12px 10px;
            border-bottom: 1px solid #e2e9ef;
            color: #1f3b4c;
        }

        .instructor-table tr:last-child td {
            border-bottom: none;
        }

        @media (max-width: 650px) {
            body {
                padding: 1rem;
            }
            .container {
                padding: 1rem;
            }
            th, td {
                padding: 10px 8px;
                font-size: 0.8rem;
            }
            .section-title {
                font-size: 1.5rem;
            }
        }

        .hr-light {
            margin: 0.5rem 0 1.8rem 0;
            height: 1px;
            background: linear-gradient(90deg, #cbdde6, transparent);
        }
    </style>
</head>
<body>
<div class="container">
    <div style="display: flex; justify-content: space-between; align-items: baseline; flex-wrap: wrap; margin-bottom: 0.5rem;">
        <h2 class="section-title">📘 Timetable · Semester Schedule</h2>
        <span style="font-size: 0.75rem; background: #eef3f7; padding: 4px 12px; border-radius: 30px; color:#2b6e5c;">EXERCISE 1</span>
    </div>
    <div class="subhead">⏰ Weekly class hours • updated spring session</div>

    <div class="timetable-wrapper">
        <table>
            <thead>
                <tr>
                    <th>Time</th>
                    <th>Monday</th>
                    <th>Tuesday</th>
                    <th>Wednesday</th>
                    <th>Thursday</th>
                    <th>Friday</th>
                </tr>
            </thead>
            <tbody>

                <tr>
                    <td>🕗 8AM – 10AM</td>
                    <td><span class="course-code">CSC569</span> (Compiler) <span class="emoji">&#127799;</span> <span class="badge">HPC</span></td>
                    <td><span class="course-code">CSC508</span> (Data Structure) <span class="emoji">&#127808;</span> <span class="badge">On</span></td>
                    <td>—</td>
                    <td>—</td>
                    <td>—</td>
                </tr>
                
                <tr>
                    <td>🕙 10AM – 12PM</td>
                    <td><span class="course-code">LCC500</span> (English) <span class="emoji">&#127810;</span> <span class="badge">BK28</span></td>
                    <td><span class="course-code">CSC508</span> (Software Engineering) <span class="emoji">&#127803;</span> <span class="badge">On</span></td>
                    <td><span class="course-code">CSC577</span> (Software Engineering) <span class="emoji">&#127803;</span> <span class="badge">MK14</span></td>
                    <td><span class="course-code">CSC584</span> (Enterprise Programming) <span class="emoji">&#127804;</span> <span class="badge">MK14</span></td>
                    <td><span class="course-code">CSC508</span> (Data Structure <span class="emoji">&#127808;</span>) <span class="badge">On</span></td>
                </tr>
               
                <tr>
                    <td>🕛 12PM – 2PM</td>
                    <td><span class="break-symbol">📖 R</span></td>
                    <td><span class="break-symbol">✏️ E</span></td>
                    <td><span class="break-symbol">🌿 H</span></td>
                    <td><span class="course-code">CSC574</span> (Web Development) <span class="emoji">&#127802;</span> <span class="badge">MK15</span></td>
                    <td><span class="break-symbol">☕ T</span></td>
                </tr>
              
                <tr>
                    <td>🕑 2PM – 4PM</td>
                    <td><span class="course-code">CSC584</span> (Enterprise Programming) <span class="emoji">&#127804;</span> <span class="badge">On</span></td>
                    <td><span class="course-code">TMC451</span> (Cina) <span class="emoji">&#127817;</span> <span class="badge">BK31</span></td>
                    <td>—</td>
                    <td>—</td>
                    <td>—</td>
                </tr>
           
                <tr>
                    <td>🕓 4PM – 6PM</td>
                    <td><span class="course-code">CSC574</span> (Web Development) <span class="emoji">&#127802;</span> <span class="badge">On</span></td>
                    <td>—</td>
                    <td>—</td>
                    <td><span class="course-code">CSC569</span> (Compiler) <span class="emoji">&#127799;</span> <span class="badge">On</span></td>
                    <td>—</td>
                </tr>
            </tbody>
        </table>
    </div>


    <div style="margin-top: 2rem;">
        <h2 class="section-title" style="margin-top: 0.2rem;">👩‍🏫 Academic Staff</h2>
        <div class="subhead">📌 course instructors & lecturers — spring term</div>
        <div class="instructor-grid">
            <table class="instructor-table">
                <thead>
                    <tr>
                        <th>Course Code</th>
                        <th>Instructor Name</th>
                    </tr>
                </thead>
                <tbody>
                    <tr><td><strong>CSC574</strong> (Web Development)</td><td>AZIZIAN BIN MOHD SAPAWI</td></tr>
                    <tr><td><strong>TMC451</strong> (Cina)</td><td>BAIDARI ESFARHANY BINTI BASRI</td></tr>
                    <tr><td><strong>LCC500</strong> (English)</td><td>DR. MUNA LIYANA BINTI MOHAMAD TARMIZI</td></tr>
                    <tr><td><strong>CSC508</strong> (Data Structure & Software Engineering)</td><td>DR. NORZILAH BINTI MUSA, PROFESOR MADYA DR SUZANA BINTI AHMAD</td></tr>
                    <tr><td><strong>CSC577</strong> (Software Engineering)</td><td>DR. MOHD SUFFIAN BIN SULAIMAN</td></tr>
                    <tr><td><strong>CSC569</strong> (Compiler)</td><td>PROFESOR MADYA DR TAJUL ROSLI BIN RAZAK</td></tr>
                    <tr><td><strong>CSC584</strong> (Enterprise Programming)</td><td>AHMAD TAUFIQ BIN HAJI MOHAMAD</td></tr>
                </tbody>
            </table>
        </div>
        <div class="hr-light" style="margin-top: 1.2rem;"></div>
        <div style="font-size: 0.75rem; text-align: right; margin-top: 0.8rem; color: #6f8faa;">✨ simplified layout • all details preserved</div>
    </div>
</div>
</body>
</html>
