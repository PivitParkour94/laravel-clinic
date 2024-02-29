# laravel-clinic
Admin portal for patient clinic admin panel

#Basis

Please create a new Laravel/Vue project, using one of the UI base projects that come with Laravel. This project should not use inertia. You can use Vite or webpack, whichever you prefer. Please use Laravel sail as we want to be able to quickly spin up and test your project locally.

Use Laravel’s built in authorization system to handle login, registration etc

Please create this as a publicly available GitHub repository. Create you main branch and initialize your Laravel project in that branch, but before creating any of the project-specific code, create a new branch and, when you are done, create a PR for your work to merge into your main branch. This PR will be what we review.

#Ontology

Please create a system that contains three models:

Clinic – this is a representation of a medical clinic

Doctor – this model represents the doctors that work at a clinic

Patient – this model represents the patients that visit the clinic

Relationships

Clinics can have many Patients and can have many Doctors. Patients can be assigned to Doctors as well.

Logic

Both Patients and Doctors can log in to the admin area you will create.

In the admin area:

Doctors can see the Clinic in which they work, and can see a list of Patients assigned to that clinic, but can only see the patients that are either currently assigned to them, or currently assigned to the Clinic but not assigned to any other Doctor.
Patients can see all Clinics and all Doctors assigned to those Clinics, but not any other Patients.
Patients can link themselves to any Doctor. When a patient links themselves to a Doctor, an email is sent to that Doctor informing them of their new patient.
When deleting a Doctor, their assigned Patients should remain linked to the Clinic.

Good luck and have fun!

