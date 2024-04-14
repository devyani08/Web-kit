# Web-kit

WEBKIT, an innovative platform designed to empower users in creating personalized website environments effortlessly. With a user-friendly interface powered by Python's Tkinter, React for dynamic updates, and efficient file handling, WEBKIT allows users to input their desired website name and craft their unique online space by adding components such as navigation bars, headers, and footers. Join us on this journey as we explore the seamless process of transforming a mere idea into a dynamic and functional website, all at the click of a button!

## How to use this repository 

## Step 1 - Installation
1.	Clone the repository from GitHub.
2.	Navigate to the project directory.
3.	You will see files like Generate.py CreateComponents.py CreateCustomComponents.py DeleteComponent.py and a Image Folder
4.	Put Images required in the projects with their naming* convention {see section 3.1}. 
## Step 2 - Create Environnment
1. Install Node.js in your machine from https://nodejs.org/en/download
2. Open the code in your IDE and write `pip install -r requirements.txt` command in terminal

## Instructions 
1. Adding Images inside Image folder
  	a. if image is a Logo of website name it as Logo.png
    b. if Using hero, name three images as Image1.png, Image2.png, Image3.png
   
2. Generating React Projects
    a.	Run the `generate.py` script.
    b.	Follow the prompts to provide the project name and Description.
    c.	The script will create a new project folder in the current directory with the specified name and generate the necessary files.
   
 3. Creating Components
    a. Run the `CreateComponents.py` script.
    b. Follow the prompts to provide the component name and Description.
    
    - Navigation: To Generate a navigation bar, write component name as `nav` and write its description, this action will lead to a default navigation bar.
    - Hero Section: To Generate a Hero Section, write component name as `Hero` and write its description, this action will lead to a default Hero Section.


  4. Using `CreateCustomComponents.py`
     -	Run the `CreateComponents.py` script.
     -	Follow the prompts to provide the component name and Description.
     
        - Navigation: To Generate a Custom navigation bar, write component name as `nav` and write its Field Items all separated by Comma [“ , ”], [For example: 
Home,About Us,Contact Us,…] this action will lead to a custom navigation bar.
        - Form Section: To Generate a Custom Form Section, write component name as `Form` and write its Field Items all separated by Comma [“ , ”], [For example: User Name,Password,Comfirm password,…] this action will lead to a Custom Form Section.


  5. Deleting Components
     -  Run the `Delete_component.py` script.
     -	Follow the prompts to select the component to delete.
     -  The script will remove the selected component folder from `src/components`.

  Note: Refer to `Web-kit.docx` for documentation
 
