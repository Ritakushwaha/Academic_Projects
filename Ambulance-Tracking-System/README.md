# Ambulance Tracking System
## Overview
This project aims to develop an Ambulance Tracking System to efficiently manage and coordinate emergency medical services. The system comprises three main modules: Patient End, Driver End, and Admin End. Each module serves specific functionalities to streamline the process of requesting, dispatching, and tracking ambulances during emergencies.

## Software Requirements
<b>Eclipse ADT Bundle:</b> Required for application creation.</br>
<b>NetBeans:</b> Necessary for servlet implementation.</br>
<b>JDK 8 with JRE:</b> Java Development Kit for running Java applications.</br>
<b>External JARs for Database:</b>
<ul><li>GSON JAR</li>
<li>MySQL Connector JAR</li>
</ul></br>
<b>External JARs for Map:</b>
<ul><li>Google Play Services JAR</li></ul>
	
## Hardware Requirements
Windows 64-bit system with 4GB or 8GB RAM.

## App Modules
### 1. Patient Module
<ul>
	<li>Patient Button: Provides functionalities including:
	<ul>
		<li>Login Screen (name, mobile number, OTP generation, submission)</li>
		<li>Critical Assistance Request</li>
		<li>Non-Critical Assistance Request</li>
		<li>Locate Nearby Hospitals</li>
		<li>Access Veterinary Hospitals</li>
	</ul>
	</li>
	<li>Voice Input: Allows navigation to the map using voice commands.</li>
</ul>

### 2. Driver Module
<ul>
	<li>Request Page: Facilitates the following actions: Display Patient's Name and Contact Number
	<ul>
		<li>Accept Request</li>
		<li>Reject Request</li>
		<li>Navigate to Patient's Location</li>
		<li>Find Nearby Hospitals</li>
		<li>Call the Patient</li>
	</ul>
	</li>
</ul>

### 3. Admin End
<ul>
	<li>Driver Details Management:
		<ul>
			<li>View, Add, Remove, and Update Driver Information.</li>
		</ul>
	</li>
	<li>Ambulance Details Management:
		<ul>
			<li>Operations to Add, Remove, and Update Ambulance Details.</li>
		</ul>
	</li>
	<li>Nearby Hospitals Management:
		<ul>
			<li>View and Manage Nearby Hospitals Information.</li>
		</ul>
	</li>
	<li>Patient Details Management:
		<ul>
			<li>Access and Manage Patient Details.</li>
		</ul>
	</li>
</ul>




