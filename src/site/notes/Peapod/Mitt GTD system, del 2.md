```dataview
    TASK
    FROM !"Config"
    WHERE !completedW
    HERE ø = "me"
    WHERE !due
    SORT file.cday desc
    ```