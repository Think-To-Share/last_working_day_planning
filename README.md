```mermaid
graph TD;
    E[Employee]--->|If not Authenticated| L[Login];
    E-->D[Dashboard];
    L-->D;
    D-->Profile;
    D-->Add_J[Add New Job Offer];
    D-->S[Search];
    S-->Apply;
    Add_J-->Cont[Get Contacted];
    Cont-->Job{Get Job};
    Apply-->Job;
```
