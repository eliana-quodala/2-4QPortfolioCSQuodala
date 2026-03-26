### Instructions:
This is individual submission in khub, but you can work with a partner. When you submit in khub please place both your names in the submission bin.

Guided Activity (30 minutes), please follow what is being required.

Make a copy of this .md file to your Q4 repository and name it as SectionLNseatwork2.md example 9LiCruzSeatwork2.md. Place it in your q4 repository vscode local computer. Committing frequently to your Github repository.
Copy the code below and paste it inside a new file (name it as SectionLNseatwork2.html). Place this file in the same location where the .md file is saved.
Change the content values of the meta tags to your names for author/s and the date today for revised.
Please do the following tasks that will ask you to reposition HTML elements then answer the guided question for each task on the .md file. Commit changes to the .md file and to the .html file as well. - This seatwork is worth 20pts and should be submitted by the end of the period The link to KHub submission bin.
Submit the links to your .md file and .html file.
<!DOCTYPE html>
<html>
<head>
  <meta name="author" content="<your names>" />
  <meta name="revised" content="<date today>" />
  <style>
    body { font-family: Arial, sans-serif; }
    .header, .footer {
      background: lightblue;
      padding: 10px;
    }
    .footer {
       opacity: 0.5;
    }
    .sidebar {
      background: lightgreen;
      width: 150px;
      height: 200px;
    }
    .content {
      background: lightyellow;
      width: 300px;
      height: 200px;
    }    
  </style>
</head>
<body>
  <div class="header">Header</div>
  <div class="sidebar">Sidebar</div>
  <div class="content">Main Content</div>
  <div class="footer">Footer</div>
</body>
</html>

### Step 1 (Static vs Relative):
Guided Question: What changed compared to the default static positioning? Try to give different values to top and left or you can change it to bottom, right.
--> answer: Compared to the default positioning, the css added simply moved the sidebar to another area, keeping all dimensions intact.

### Step 2 (Fixed):
Guided Question: What happens when you scroll the page? Why does the footer behave differently from position relative?
--> answer: It behaves differently from relative since relative moves the container based on specific dimensions written. position:fixed makes it so the footer overlaps the rest of the document.

### Step 3 (Absolute): 
Guided Question: What is the effect of position: absolute on an element? How is it different from fixed?
--> answer: Position:absolute has a fixed area so other elements have to move around it. It's only visible when you scroll to the page it's on, while fixed remains constant on your screen as you go through the webpage. 

### Step 4 (Absolute):
Guided Question: Why does the notice appear on top of the content? What happens if you swap the z‑index values?
--> answer: The z index values cause unusual overlapping of elements. if we swap z values, the content will go on top of notice.

## Challenge
What changes that you have to do on the code that will position .notice box on the top right corner of the .content box? Please write the code on paper as well (both html and css on the part of .notice and .content).
--> answer: 

Try to change the position of .content to relative then to fixed. What do you observed each time?
--> answer: 

What do you observe on about the effect of z-index on .notice and .content boxes?
--> answer: 