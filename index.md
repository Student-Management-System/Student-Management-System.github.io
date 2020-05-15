# Overview
![Overview](https://raw.githubusercontent.com/Student-Management-System/std-mgmt.io/master/figures/Overview.svg)

# Tools and Repositories
<table>
	<tbody>
		<tr>
			<th>Tool</th>
			<th>Description</th>
			<th>Type</th>
			<th>Status</th>
		</tr>
		
		<tr>
			<th colspan="4" style="text-align:center;background:#666666">Web Services</th>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/Sparkyservice-Project/">Sparkyservice</a></td>
			<td>Access control of services, authentification, user profiles</td>
			<td>REST Service</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_Sparkyservice-Project" alt="Build status of Sparkyservice-Project"></td>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/StudentMgmt-Backend/">Student-Management-Backend</a></td>
			<td>Student-Management-Backend (management of courses, groups, homework, assessments)</td>
			<td>REST Service</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_StudentMgmt-Backend" alt="Build status of Student-Management-Backend"></td>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/StudentMgmt-Client/">Student-Management-Client</a></td>
			<td>Student-Management-Client (UI of the Backend)</td>
			<td>Web server</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_StudentMgmt-Client" alt="Build status of Student-Management-Client"></td>
		</tr>
		
		<tr>
			<th colspan="4" style="text-align:center;background:#666666">Java Server Tools</th>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/Rights-Management">Rights-Management</a></td>
			<td>Configures the Java submission server according to the settings of the StudentMgmt-Backend</td>
			<td>Java Application</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_Rights-Management" alt="Build status of Rights-Management"></td>
		</tr>
		<tr>
			<td>Submission Hook</td>
			<td>Tests submissions and sends intermediate assessment results to the StudentMgmt-Backend</td>
			<td>Java Application</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_jSvnSubmitHook_2.0" alt="Build status of jSvnSubmitHook_2.0"></td>
		</tr>
		
		<tr>
			<th colspan="4" style="text-align:center;background:#666666">Java User Tools</th>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/Submitter-Protocol">Submitter-Protocol</a></td>
			<td>Java network protocol for the ExerciseSubmitter and ExerciseReviewer tools.</td>
			<td>Java Library</td>
			<td><img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_Submitter-Protocol" alt="Build status of Submitter-Protocol"></td>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/StandaloneSubmitter/">StandaloneSubmitter</a></td>
			<td>Standalone version of the Java ExerciseSubmitter.</td>
			<td>Java Application</td>
			<td>
				<img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_ExerciseSubmitter" alt="Build status of ExerciseSubmitter">
				<img src="https://jenkins-2.sse.uni-hildesheim.de/buildStatus/icon?job=Teaching_ExerciseSubmitter-v2" alt="Build status of ExerciseSubmitter (REST-based)">
			</td>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/ExerciseSubmitter">Eclipse ExerciseSubmitter</a></td>
			<td>Java ExerciseSubmitter as Eclipse Plug-in.</td>
			<td>Eclipse Plug-in</td>
			<td style="text-align:center;"><img src="https://raw.githubusercontent.com/Student-Management-System/std-mgmt.io/master/figures/missing.svg" height="20" alt="Build status of Eclipse ExerciseSubmitter"></td>
		</tr>
		<tr>
			<td><a href="https://github.com/Student-Management-System/ExerciseReviewer">Eclipse ExerciseReviewer</a></td>
			<td>Reviewer for the tutors to correct and assess homework.</td>
			<td>Eclipse Plug-in</td>
			<td style="text-align:center;"><img src="https://raw.githubusercontent.com/Student-Management-System/std-mgmt.io/master/figures/missing.svg" height="20" alt="Build status of Eclipse ExerciseReviewer"></td>
		</tr>
	</tbody>
</table>
