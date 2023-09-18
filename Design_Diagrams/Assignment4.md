# Army ROTC Website Design Diagram
The goal for my project is to improve the UC Army ROTC website in order to improve communication within the Battalion and increase recruitment and retention within the program.

```
Text boxes represent actions items that appear or actions that could occur.
Lines between text boxes represent something that follows a previos action or an action that will occur.
```

### Design D0
```mermaid
flowchart TD;
  A(Website Opened)-->B(Homepage Appears)
  B-->C(Navbar Displayed)
  C-->D(Navbar Item Clicked)
  D-->E(Route to New Page)
  E-->F(Side Menu Displayed)
  F-->G(Side Menu Item Clicked)
  G-->E

  E-->C
```


### Design D1
```mermaid
flowchart TD;
  A(Route to New Page)-->B(Page Displays Important Information)
  A-->C(Links on the Left Side)
  A-->D(Navbar Displayed)
  C-- Clicked -->A
  D-- Clicked -->A
```

### Design D2
```mermaid
flowchart LR;
  A(Navbar Items)-->B(Cadet Training Information)
  A-->C(Meet Our Cadre)
  A-->D(Army Regulations and Training Doctrine)
  A-->E(Newsletter and Weekly SITREP)
  A-->F(Opportunities)
  A-->G(Join Today)

  B-->B1(Events Calendar)
  B-->B2(This Week)
  B-->B3(Trackers)

  C-->C1(PMS)
  C-->C2(SMI)
  C-->C3(APMS)

  D-->D1(AR 670-1)
  D-->D2(FM 3-21.76)
  D-->D3(ATP 3-21-8)

  E-->E1(Weekly SITREP)
  E-->E2(Newsletter)

  F-->F1(Branches)
  F-->F2(Army Schools)
  F-->F3(Tuition Assistance)
  F-->F4(CTLT)

  G-->G1(Mr. Prows)
```
