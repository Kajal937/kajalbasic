## What Is Jinja2 ?
Jinja2 is a popular and powerful templating engine for Python programming. It is used to generate dynamic content in various
applications, such as web development, configuration management, and more. 
Templating languages allow creation of text based documents where some of the content can be dynamically generated. Resulting files can be HTML, JSON, XML, or anything.

For data format:
YAML file
JSON file

## Where Is It Used ?
Some notable(Famous) examples of applications using Jinja2 are Ansible, Django, Flask, Salt and Trac.

## Advantages and Why we use jinja?

Clarity:
Jinja2 helps keep things neat and organized. It separates the code that does the work (like fetching data) from how the data is displayed (like creating a webpage).
Flexible: 
Flexibility means the ability to adapt or change easily to different situations or needs.

## Why Would I Want To Use It?
Web frameworks like Flask and Django, or automation ones like Ansible and Salt, provide out of the box support for Jinja.
Ansible even uses a lot of the Jinja syntax in its Playbooks.

Ansible - Ansible is an open-source automation tool(For example, if you want to install software on multiple computers, you can use an automation tool to do it on all of them simultaneously, saving you time and effort.) that allows you to define infrastructure as code and automate tasks such as configuration management, application deployment.
SaltStack (Salt) - Salt is another infrastructure automation and configuration management tool. It is also similar to Ansible.
Ansible uses playbooks to declare tasks.

Static Template:
A static template is a fixed, unchanging template that contains predefined content.
Dynamic Template:
It can change based on input data and conditions.

## How Does It Work?
Jinja2 essentially needs two source ingredients, template and data that will be used to render the final documents.

## The syntax of Jinja2 templates is straightforward and uses double curly braces ({{ }}) to enclose expressions, variables, or statements
1. Variables: To insert a variable's value into the template, use double curly braces with the variable name inside, like this:
Hello, {{ name }}!
2. Expressions: You can use Jinja2 expressions to perform operations or evaluations within the template. For example:
The total is {{ num1 + num2 }}.
3. Filters: Filters are used to modify variables or expressions before displaying them. Filters are applied using the pipe (|) character. 
The price is {{ price | currency('USD') }}.

4. Conditions: You can use {% if %} and {% endif %} tags for conditional statements:
{% if score >= 60 %}
You passed the exam!
{% else %}
You didn't pass the exam.
{% endif %}

5. Loops: {% for %} and {% endfor %} tags are used for looping:
<ul>
{% for item in items %}
  <li>{{ item }}</li>
{% endfor %}
</ul>

6. Comments: You can add comments using {# #} tags:
{# This is a comment and won't be displayed in the output #}










#C++ template 
A template is a pre-designed format or layout used as a starting point for creating documents, web pages, or other content.
In C++, a template is a way to write generic code( refers to code that is written to work with multiple data types) that can work with different data types. Think of it as a blueprint for creating functions or classes that can be customized to work with various types of data
