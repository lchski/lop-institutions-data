# LOP institutions data

Holds the JSON underlying the LOP's ["Departments and Roles: 1867 - Today" table](https://lop.parl.ca/sites/ParlInfo/default/en_CA/Federal/areasResponsibility).

To be used in conjunction with [`lchski/parliamentarians-analysis`](https://github.com/lchski/parliamentarians-analysis) (the institutional portion may move into its own repo at some point, who knows).


## Downloading

`https://lop.parl.ca/ParlInfoWebAPI/Organization/GetAreaOfResponsibilityList?callback=1`, then edit out the JSONP and save as `departments.json`. Yay, manual downloading!

