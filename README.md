<h1 align="center">Hugo Blowfish Decap CMS Starter 🚀</h1>
<br>

[![CodeQL](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/actions/workflows/codeql.yml/badge.svg)](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/actions/workflows/codeql.yml)
[![Dependency review](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/actions/workflows/dependency-review.yml)
[![Minimum Hugo Version](https://img.shields.io/static/v1?label=min-HUGO-version&message=0.87.0&color=blue&logo=hugo)](https://github.com/gohugoio/hugo/releases/tag/v0.87.0)
[![GitHub](https://img.shields.io/github/license/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter)](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/blob/main/LICENSE)
[![Code Size](https://img.shields.io/github/languages/code-size/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter)](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter)

## Decap CMS

Decap CMS is a Content Management System designed to work seamlessly with the [Blowfish Theme](https://github.com/nunocoracao/blowfish), a popular website builder theme. It leverages the power of Decap CMS and integrates with Netlify Identity to provide a comprehensive content management solution for your website projects.

## Features

- **Blowfish Theme Integration**: Decap CMS is specifically tailored to integrate smoothly with the Blowfish Theme, ensuring a cohesive and intuitive content management experience.
- **User-Friendly Interface**: Decap CMS provides a user-friendly interface that allows content editors and administrators to manage website content efficiently without requiring technical expertise.
- **Netlify Identity Integration**: With Netlify Identity integration, Decap CMS offers secure authentication and user management capabilities, allowing you to control access to content editing features based on user roles.
- **Flexible Content Management**: Easily create, edit, and publish content such as pages, posts, media files, and more using Decap CMS. The system provides flexible content structuring options to suit your website's needs.

## Getting Started

To get started with Decap CMS and the Blowfish Theme integration:

1. **Clone the Repository**: Clone the [Blowfish Theme](https://github.com/nunocoracao/blowfish) repository and set up your local development environment following the theme's documentation. For detailed instructions on installing the Blowfish Theme, refer to the [Blowfish Theme Installation Documentation](https://blowfish.page/docs/installation/).

2. **Install Decap CMS Module**:
   - Follow the instructions in the [Decap CMS Module Repository](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/) to install the Decap CMS module within your project.
   - Configure the integration settings for the Blowfish Theme to ensure seamless compatibility.

### Install Decap CMS Module

Edit your project's configuration file based on the format you are using (YAML, TOML, or JSON) to import the `Hugo-Blowfish-Decap-CMS-Starter ` module:

#### config/_default/config.toml
```toml
    [module]
    [[module.imports]]
    path = "github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter"
```
---
#### config/_default/config.yaml
```yaml
   module:
     imports:
       - path: github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter
```
---
#### config/_default/config.json
```json
    {
    "module": {
        "imports": [
        {
            "path": "github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter"
        }
        ]
    }
    }
```
 3. **Configure Parameters**:
   - Edit the `config/_default/params.toml` file to define parameters for your project. For example:

 ```toml
     [DecapCMS]
      development = true
      # branch = ""
      media = "/static/images"
      public = "/images"
      PublishMode = "editorial_workflow"
      # logo = ""
      preview = true
      search = false
 ```
 #### config/_default/params.yaml
 ```yaml
     DecapCMS:
      development: true
      # branch: ""
      media: "/static/images"
      public: "/images"
      PublishMode: "editorial_workflow"
      # logo: ""
      preview: true
      search: false
 ```
 #### config/_default/params.json
 ```json
{
  "DecapCMS": {
    "development": true,
    // "branch": "",
    "media": "/static/images",
    "public": "/images",
    "PublishMode": "editorial_workflow",
    // "logo": "",
    "preview": true,
    "search": false
  }
}
     
 ```

   Update the parameters according to your project's requirements. 
   
 4. **Configure Netlify Identity**: If you plan to deploy your website on Netlify, configure Netlify Identity to enable user authentication and access control for Decap CMS.
 5. **Start Managing Content**: Once everything is set up, you can start managing your website's content using Decap CMS. Create pages, add media, and manage user access as needed.

 ## Documentation

 For detailed documentation and guides on using Decap CMS with the Blowfish Theme and Netlify Identity, refer to the following resources:

 - [Decap CMS Documentation](https://decapcms.org/docs)
 - [Blowfish Theme Documentation](https://github.com/nunocoracao/blowfish)
 - [Netlify Identity Documentation](https://docs.netlify.com/visitor-access/identity/)

 ## Support and Feedback

 If you encounter any issues, have questions, or want to provide feedback, please open an issue in the respective repositories or contact the project maintainers.

 - [Decap CMS GitHub Repository](https://github.com/decapcms/decap)
 - [Blowfish Theme GitHub Repository](https://github.com/nunocoracao/blowfish)
 - [Hugo Blowfish Decap CMS Starter GitHub Repository](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/)

 ## Contributing

 Feel free to contribute by submitting issues or pull requests.

 ## License

 This project is licensed under the [MIT License](https://github.com/Armoghan-ul-Mohmin/Hugo-Blowfish-Decap-CMS-Starter/blob/main/LICENSE).
