---
sidebar_position: 3
---

# Create a patient

Now that you've registered an account, let's add some data. This tutorial explains how to create a [Patient](../api/fhir/resources/patient) in the Medplum app.

- Open the Medplum app in your browser: https://app.medplum.com/. (If you don't have an account yet, see the [Register tutorial](./register))
- Click on the menu button in the top left corner

![Top left menu](/img/hello-world/top-left-menu.png)

- Click on "Patients"

  <img alt='Patients' menu item src='/img/hello-world/patients-menu-item.png' style={{maxWidth: '75%'}}/>

- Click on "New" in the toolbar

![New Patient button](/img/hello-world/new-patient-button.png)

Let's create a patient with only a few fields. We can always add more later. We will add a name, gender, and date of birth.

Patients in Medplum can have multiple names, depending on the usage. Let's add our first name:

- Scroll down to the "Name" section.
- Click the "+" button to the right.
- Enter the patient's first name (i.e. their "given name") in the "Given" field.
- Enter the patient's last name (i.e. their "family name") in the "Family" field.

![Patient name](/img/hello-world/patient-name.png)

Next we'll set the patient's gender, which will be one of the FHIR [Administrative Gender](https://www.hl7.org/fhir/valueset-administrative-gender.html) values.

- Scroll down to "Gender".
- Start typing a gender such as "male", "female", or "other".
- Use the autocomplete functionality to choose the desired value.

Finally, we'll set the patient's date of birth

- Scroll down to "Birth Date".
- Enter a date of birth in the date picker.

Scroll to the bottom and click "OK" to save your changes.

<img alt='OK Button' menu item src='/img/hello-world/ok-button.png' style={{maxWidth: '75%'}}/>

Congrats, you created a patient!