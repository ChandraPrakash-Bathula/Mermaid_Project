graph TD
A((Student Website)) --> B(Backlog Creation)
B --> C(Sprint Planning)
C -->D{Sprint 1}
D --> D1[Design Login Page]
D --> D2[Setup Database]
D --> D3[Implement Authentication]
D1-->E1[Code Review]
D2-->E2[Code Review]
D3-->E3[Code Review]
E1-->F1[Test Login Page]
E2-->F2[Test DB Connection]
E3-->F3[Test Authentication Security]
F1-->G1[Sprint1 Review]
F2-->G1
F3-->G1
G1-->H1[Sprint Retrospective]
H1-->I{Sprint2}
I-->I1[Student Activities Dashboard]
I-->I2[Add Course]
I1-->J1[Test Dashboard]
I2-->J2[Test Course Flow]
J1-->K1[Sprint 2 Review]
J2-->K1
K1-->L((Deployment and Maintenance))
