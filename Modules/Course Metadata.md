<h1>Advanced Settings</h1>
<hr />
<h4>Advanced Module List</h4>
<h6>It indicates what advanced modules used in your course</h6>
<h6>Put the modules's name (with quotation marks) in square brackets, and separates each using comma.</h6>
<h6>This property only accept the regular json data, please be careful with the usage of comma, colon, quotes</h6>
<pre><code>advanced_modules:[
	&quot;lti_consumer&quot;,
	&quot;library_content&quot;
]
</code></pre>
<hr />
<h4>Certificate Name (Long)</h4>
<h6>Use this setting only when generating PDF certificates. Between quotation marks, enter the long name of the type of certificate that students receive when they complete the course. For instance, &quot;Certificate of Achievement&quot;.</h6>
<h6>the $CourseTitle$ is a placeholder of Course Title, code will use the real course title to replace it</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>cert_name_long:&quot;$CourseTitle$ Certificate&quot;
</code></pre>
<hr />
<h4>Certificate Name (Short)</h4>
<h6>Use this setting only when generating PDF certificates. Between quotation marks, enter the short name of the type of certificate that students receive when they complete the course. For instance, &quot;Certificate&quot;.</h6>
<h6>the $CourseTitle$ is a placeholder of Course Title, code will use the real course title to replace it</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>cert_name_short:&quot;$CourseTitle$ Certificate&quot;
</code></pre>
<hr />
<h4>Certificate Web/HTML View Enabled</h4>
<h6>It indicates if Web/HTML views are enabled for the course or not</h6>
<h6>The allowed values is: true or false</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>cert_html_view_enabled:true
</code></pre>
<hr />
<h4>Certificates Display Behavior</h4>
<h6>Use 'end', 'early_with_info', or 'early_no_info'. After certificate generation, students who passed see a link to their certificates on the dashboard and students who did not pass see information about the grading configuration. The default is end, which displays this certificate information to all students after the course end date. To display this certificate information to all students as soon as certificates are generated, enter early_with_info. To display only the links to passing students as soon as certificates are generated, enter early_no_info.</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>certificates_display_behavior:&quot;early_with_info&quot;
</code></pre>
<hr />
<h4>Course Card Image (Course Image)</h4>
<h6>It indicates what image will be used as the course image</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>course_image:&quot;images_course_image.jpg&quot;
</code></pre>
<hr />
<h4>Course Display Name</h4>
<h6>It indicates what name will be used as the name in the course list</h6>
<h6>the $CourseTitle$ is a placeholder of Course Title, code will use the real course title to replace it</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>display_name:&quot;$CourseTitle$&quot;
</code></pre>
<hr />
<h4>Course Number Display String</h4>
<h6>Enter the course number that you want to appear in the course.</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>display_coursenumber:&quot;&quot;
</code></pre>
<hr />
<h4>Course Visibility In Catalog</h4>
<h6>Defines the access permissions for showing the course in the course catalog. This can be set to one of three values: 'both' (show in catalog and allow access to about page), 'about' (only allow access to about page), 'none' (do not show in catalog and do not allow access to an about page).</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>catalog_visibility:&quot;none&quot;
</code></pre>
<hr />
<h4>LTI Passports</h4>
<h6>Enter the passports for course LTI tools in the following format: &quot;id:client_key:client_secret&quot;.</h6>
<h6>This property only accept the regular json data, please be careful with the usage of comma, colon, quotes</h6>
<pre><code>lti_passports:[
    &quot;passportid1:key1:secret1&quot;,
    &quot;xtreme:LaaS:7cf54114490f4b95ae1b990266ccc6cb&quot;
]
</code></pre>
<hr />
<h4>Maximum Attempts</h4>
<h6>Enter the maximum number of times a student can try to answer problems. By default, Maximum Attempts is set to 2, if it is set to null, meaning that students have an unlimited number of attempts for problems. You can override this course-wide setting for individual problems. However, if the course-wide setting is a specific number, you cannot set the Maximum Attempts for individual problems to unlimited.</h6>
<pre><code>max_attempts:2
</code></pre>
<hr />
<h1>Grading Setting</h1>
<h4>Overall Grade Range</h4>
<h6>This property only accept the regular json data, please be careful with the usage of comma, colon, quotes</h6>
<pre><code>GRADE_CUTOFFS: {
		&quot;Pass&quot;:0.75
    }
</code></pre>
<hr />
<h4>GRADER</h4>
<h6>This property only accept the regular json data, please be careful with the usage of comma, colon, quotes</h6>
<pre><code>GRADER: [
        {
            &quot;drop_count&quot;: 0, 
            &quot;min_count&quot;: 4, 
            &quot;short_label&quot;: &quot;Quiz&quot;, 
            &quot;type&quot;: &quot;Knowledge Check&quot;, 
            &quot;weight&quot;: 0.4
        }, 
        {
            &quot;drop_count&quot;: 0, 
            &quot;min_count&quot;: 1, 
            &quot;short_label&quot;: &quot;Lab&quot;, 
            &quot;type&quot;: &quot;Lab&quot;, 
            &quot;weight&quot;: 0.3
        },
        {
            &quot;drop_count&quot;: 0, 
            &quot;min_count&quot;: 1, 
            &quot;short_label&quot;: &quot;Final&quot;, 
            &quot;type&quot;: &quot;Final Exam&quot;, 
            &quot;weight&quot;: 0.3
        }
    ]
</code></pre>
<hr />
<h1>Schedule And Details Settings</h1>
<h4>Course Pacing</h4>
<h6>It indicates if enable Self-Paced</h6>
<h6>allowed Value: true or false</h6>
<h6>if assigns to 'false', the platform use Instructor-Paced mode. otherwise (assigns to 'true'), the platform use Self-paced mode.</h6>
<h6>Instructor-paced courses progress at the pace that the course author sets. You can configure release dates for course content and due dates for assignments.</h6>
<h6>Self-paced courses do not have release dates for course content or due dates for assignments. Learners can complete course material at any time before the course end date.</h6>
<pre><code>self_paced:true
</code></pre>
<hr />
<h4>Course Start Date</h4>
<h6>First day the course begins</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>start: &quot;2017-08-08T01:00:00Z&quot;
</code></pre>
<hr />
<h4>Course End Date</h4>
<h6>Last day your course is active</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>end: &quot;2027-12-31T23:59:00Z&quot;
</code></pre>
<hr />
<h4>Enrollment Start Date</h4>
<h6>First day students can enroll</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>enrollment_start: &quot;2017-08-08T01:00:00Z&quot;
</code></pre>
<hr />
<h4>Enrollment End Date</h4>
<h6>Last day students can enroll</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>enrollment_end: &quot;2027-12-31T23:59:00Z&quot;
</code></pre>
<hr />
<h4>Language</h4>
<h6>Identify the course language here. This is used to assist users find courses that are taught in a specific language.</h6>
<h6>Use the Language Codes to identifu the language.</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>Language:&quot;en&quot;
</code></pre>
<hr />
<h4>Hours of Effort in total</h4>
<h6>Time spent on all course work.</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>effort:&quot;14-26 hours in total&quot;
</code></pre>
<hr />
<h4>Course Short Description</h4>
<h6>Appears on the course catalog page when students roll over the course name. Limit to ~150 characters</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>course_short_description:&quot;This is the course short description1&quot;
</code></pre>
<hr />
<h4>Course Introduction Video</h4>
<h6>Enter your YouTube video's ID (along with any restriction parameters)</h6>
<h6>Notice that the value of this property should be in a pair of quotes</h6>
<pre><code>about_video_id:&quot;3_yD_cEKoCk&quot;
</code></pre>
<hr />
<h1>Other Settings</h1>
<hr />
<h4>Video Upload Credentials</h4>
<h6>The unique identifier for your course's video files provided by edX</h6>
<h6>This property only accept the regular json data, please be careful with the usage of comma, colon, quotes</h6>
<pre><code>video_upload_pipeline:{
 &quot;course_video_upload_token&quot;:&quot;958caaa64c6611e7af70127a4fc0bc92&quot;
}
</code></pre>
<hr />
<h1>MILT Settings</h1>
<hr />
<h4>Course Number used for MILT</h4>
<h6>Enter the milt course nunmber</h6>
<pre><code>milt_coursenumber:&quot;INF-999T01&quot;
</code></pre>
<hr />
<h4>Course instance number used for MILT</h4>
<h6>Enter the milt instance nunmber</h6>
<pre><code>milt_instanceNumber:&quot;2018_Q3A&quot;
</code></pre>
<hr />
<h4>Course cover image file name used for MILT</h4>
<h6>Enter the cover image file name for milt, the file should be in the About_page/</h6>
<pre><code>milt_instanceNumber:&quot;2018_Q3A&quot;
</code></pre>
