# Skillbox Platform Course Analytics

The business goal of this project is to prepare an analytics report based on which course creators and editors can update and improve the courses. 

A brief analytical description for each course will be formed first based on the calculated metrics. Then potential course instructor workload will be calculated to evaluate the need to hire more employees. After that, course content quality will be investigated to potentially identify problematic modules that require revision. Finally, presence of seasonal variation will be investigated.

The `progress_phases.csv` dataset was too large to upload to the repository, so it can be downloaded [here](https://drive.google.com/file/d/1uejxyeuFtVLNOZtl_3W85o9U2xdpKogM/view?usp=sharing)

## Codebook

`courses.csv` contains the following columns: <br><br>
&nbsp;&nbsp;&nbsp;&nbsp; `id` - course id <br>
&nbsp;&nbsp;&nbsp;&nbsp; `title` – course title <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `field` – type of the course <br> <br><br>
`students.csv` contains the following columns: <br><br>
&nbsp;&nbsp;&nbsp;&nbsp; `id` – student id <br>
&nbsp;&nbsp;&nbsp;&nbsp; `city` – student's city of residence <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `birthday` – student's birthday <br> <br><br>
`course_contents.csv` contains the following columns: <br><br>
&nbsp;&nbsp;&nbsp;&nbsp; `course_id` – course id <br>
&nbsp;&nbsp;&nbsp;&nbsp; `module_number` – number of the module within a course <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `module_title` – module title <br> 
&nbsp;&nbsp;&nbsp;&nbsp; `lesson_number` – number of the lesson within a module <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `lesson_title` – lesson title <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `lesson_token` – internal lesson identification token <br> 
&nbsp;&nbsp;&nbsp;&nbsp; `is_video` – whether a video is present in the lesson *(true/false)* <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `is_homework` – whether the lesson is a homework *(true/false)* <br>
<br><br>
`progresses.csv` contains the following columns: <br><br>
&nbsp;&nbsp;&nbsp;&nbsp; `id` – progress id <br>
&nbsp;&nbsp;&nbsp;&nbsp; `student_id` – student id <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `course_id` – course id <br> <br><br>
`progress_phases.csv` contains the following columns: <br><br>
&nbsp;&nbsp;&nbsp;&nbsp; `progress_id` – progress id <br>
&nbsp;&nbsp;&nbsp;&nbsp; `module_number` – module number <br>
&nbsp;&nbsp;&nbsp;&nbsp; `lesson_number` – number of the lesson within a module <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `status` – lesson completion status <br>
&nbsp;&nbsp;&nbsp;&nbsp;  `start_date` – lesson start date <br> 
&nbsp;&nbsp;&nbsp;&nbsp; `finish_date` – lesson finish date <br>
<br><br>

