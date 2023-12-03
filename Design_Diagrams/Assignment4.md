# Army ROTC Website Design Diagram
The goal for my project is to improve the UC Army ROTC website in order to improve communication within the Battalion and increase recruitment and retention within the program.

```
Text boxes represent actions items that appear or actions that could occur.
Lines between text boxes represent something that follows a previos action or an action that will occur.
```

### Design D0
```mermaid
flowchart TD;
  A(Website Opened)-->B(Navbar displayed at top of page)
  B-->C(Navbar Item Clicked)
  C-->D(Route to area on Page)
  D-->E(Information populates with animations)
```


### Design D1
```mermaid
flowchart TD;
  A(Route to New area of Page)-->B(Page Displays Important Information)
  A-->C(Navbar reamins displayed on top)
  B-- Clicked -->A
  C-- Clicked -->A
```

### Design D2
```mermaid
flowchart LR;
  A(Navbar Items)-->B(About)
  A-->C(Timeline)
  A-->D(Branches)
  A-->E(Contact)

  B-->B1(Summary of ROTC)
  B-->B2(Graphic in middle)
  B-->B3(Stats on side)
  B-->B4(Social Media)

  C-->C1(Timeline of ROTC)

  D-->D1(Branches displayed)
  D-->D2(load more button)
  D-->D3("See details" button when hovering)

  E-->E1(Map of battalion)
  E-->E2(form to contact our office)
```
