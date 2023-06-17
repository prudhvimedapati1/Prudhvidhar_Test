# Prudhvidhar_Test

Q1.
Every Internet webpage contains two main divisions namely Front-end and Back-end. First, let's talk about the front-end part of the webpage.

Front-end:
The front end mainly refers to the part in which the user can interact directly. It might be the text, the elements he sees, or the buttons he can press to do some task.

	Some of the most basic and most important technologies used in front end development are HTML(Hyper Text Markup Language) which defines the basic skeletal structure of the webpage, CSS(Cascading Style Sheets) which is used to style the website according to our liking and Javascript which gives functionality to the website.

Back-end:
	The back end is mainly about what’s happening behind the scenes of a website. It generally has a server, a database, and the logic for the application.
It usually takes a request and gives a response to the user.

	Some of the technologies used are nodeJS, PHP, Ruby, etc. The most common databases are MySQL, MongoDB, etc. Some of the frameworks are ExpressJS, Django, etc.


Q2.
Tags in HTML.

1. Division Tags:
	Div tags are used to create sections of other elements and style them together.
Example: 
<div>
  	<h1>Title</h1>
  	<p> content of the section.</p>
	<div>(some other block)</div>
</div>
2. Heading Tags:
	Heading tags are used to define different levels of headings on the webpage, the h1 tag has the highest hierarchy, and then h2, and so on.
Example:
<h1>Title</h1>
<h3>Subtitle</h3>

3. Paragraph Tags:
	Paragraph tags are used to write some block of text or a paragraph.
Example:
<p>Good Morning everyone. This is my paragraph</p>

4. Image Tags:
	Image tags are used to put images on the webpage. They take an attribute called “src” in which we need to provide the URL or the path of the image.
Example:
<img src="../folder/photo.jpg" alt=" alternate text if the image is failed to display">

5. Link Tags:
	Link tags are used to create hyperlinks from which users can shift to other web pages as intended. They take an attribute called “href” in which we provide the endpoint URL.
Example:
<a href="https://www.facebook.com/user">Visit my facebook</a>

6. List Tags:
	These are used to show a list of items. They can be ordered lists(<ol>) or unordered lists(<ul>). The list items are defined by <li> tag.
Example:
<ul>
	<li> first item</li>
	<li> second item </li>
</ul>

7. Form Tags:
	Form tags are used to create forms to take input from the users. They use input tags to take the input and button tags to submit the form.
Example:
<form>
  <input type="text">
  <button type="submit">Submit</button>
</form>

8. Table Tags:
	Defines tables. <tr> tag for rows and <td> tag for data inside them.
Example:
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
    <td>Data 3</td>
  </tr>
</table>


Q3.
Virtual DOM:
	The Virtual DOM (VDOM) is a concept in web development used by frameworks like React. It works by creating a lightweight JavaScript representation of the actual browser DOM(Document Object Model).
When you want to update a component, a new Virtual DOM tree is generated and compared with the previous virtual one. By efficiently analyzing the differences, only the necessary changes are made to the real DOM, resulting in better performance. 
By using the Virtual DOM, React reduces the number of direct manipulations to the real DOM, which can be computationally expensive. Instead, it optimizes the process by updating only the required parts of the DOM, leading to faster rendering and improved performance. The Virtual DOM serves as an intermediary layer between your React components and the actual browser DOM, allowing React to efficiently update the user interface while maintaining a declarative programming model.

Q4. 
MySQL vs NoSQL

1. Data  Model:
	MySQL is a relational data model with tables, rows, and columns.
NoSQL has different data models such as key-value pairs, documents, or graph which can be considered as flexible and has a dynamic schema.

2. Schema:
	MySQL is structured with a fixed schema that defines the table structure, data types, and relationships.
NoSQL is a schema-less model, which allows the data to be flexible. Data can be added without a predefined structure.

3. Use Cases:
	MySQL is well-suited for applications with structured data and complex relationships, such as banking systems or e-commerce platforms.
NoSQL is often preferred for handling unstructured or semi-structured data, real-time analytics, content management systems, and social media platforms.


Q5.
MongoDB
	Let’s talk about MongoDB, which is a NoSQL database management system(DBMS)”.
	MongoDB is a document-oriented DBMS technology that falls under the NoSQL category. Unlike traditional relational databases, MongoDB stores data in flexible, self-contained documents in the BSON (Binary JSON) format.
	MongoDB operates on a collection-document model. A collection is a grouping of related documents, and each document represents a single record with its own unique structure. These documents can have varying fields, sizes, and nested structures, providing flexibility.
	MongoDB's schema-less design allows for agile development, as changes to the data model can be accommodated without altering the entire database structure. This flexibility is particularly beneficial for projects with evolving or unstructured data, such as content management systems, real-time analytics, and social media apps.
	
