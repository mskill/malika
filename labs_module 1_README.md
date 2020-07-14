# Module 1

This is a sample module of the Skills Network Courses Labs. With Skills Network, you would be able to create three different types of Course labs.

- [JupyterLab-based Course Labs](#jupyterLab-based-course-labs)
- [Theia-based Course Labs](#theia-based-course-labs)
- [Instructional Course Labs](#instructional-course-labs)

## JupyterLab-based Course Labs

With JupyterLab, you would be able to deliver hands-on Data Science experience to learners.

### Example

Some example of such labs include:

- a Jupyter Notebook to teach learners how to use Deep Learning to perform image classification
- a Jupyter Notebook to teach learners how to use Python to analyze data

### Authoring

To prepare and author a JupyterLab-based course labs, go to [SN Labs](https://labs.cognitiveclass.ai/tools/jupyterlab/) and create a new Notebook file.

Upon finishing, download the Notebook file and upload the file to the GitLab project for your course. You can find the link to your GitLab project at [Author Workbench](https://author.skills.network/courses). For instruction regarding how to upload files to GitLab, learn more at this [article](https://support.cognitivefaculty.com/knowledgebase/articles/1944787-how-to-upload-manage-course-assets-on-gitlab).

## Theia-based Course Labs

Theia-based Course Labs are coding labs that utilize theia-based tools ([Theia](https://labs.cognitiveclass.ai/tools/theia/), [Theia with Docker](https://labs.cognitiveclass.ai/tools/theiadocker/), and [Theia with OpenShift](https://labs.cognitiveclass.ai/tools/theiaopenshift/)) in SN Labs.

### Example

Some examples of such labs include:

- a quick tutorial of deploying a Node.js web server on Cloud Foundry
- a quick tutorial to explain how to deploy web services on OpenShift
- a quick tutorial of explaining a feature of a programming language

### Authoring

Please use [coding-labs.md](./coding-labs.md) as a template to get started.

You can directly edit the file on GitLab. Upon finishing, we automatically provide you with a URL that you can use to publicly share and access your content. The link is available in the **Asset Library** for your project, you may find the link in the course detail page on [Author Workbench](https://author.skills.network/courses).

## Instructional Course Labs

Instructional Course Labs are a set of instructions for the learner to follow that do not require use of tools on SN Labs.

### Example

Some examples of such labs include:

- a lab to sign up for IBM Cloud and provision a specific service like Watson Studio
- a lab to use a service on IBM Cloud to perform a specific set of tasks like running queries on Db2 console
- a lab with to perform certain tasks in Excel online
- a lab to signup and introduce GitHub / GitLab basics and concepts

### Authoring

Please use [instructional-labs.md](./instructional-labs.md) as a template to get started.

You can directly edit the file on GitLab. Upon finishing, we automatically provide you with a URL that you can use to publicly share and access your content. The link is available in the **Asset Library** for your project, you may find the link in the course detail page on [Author Workbench](https://author.skills.network/courses).

For all markdown (`.md`) file, a HTML version is automatically generated and uploaded to the **Asset Library**. A `.html` extension is appended after the original file name. For example, a HTML version of `instructional-labs.md` will be `instructional-labs.md.html`. This provide you the flexibility to embed instructional course labs directly on distribution platforms, such as, edX and Coursera.