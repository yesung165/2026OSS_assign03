# Lakers Roster Manager — CRUD Frontend UI

A Multi-Page CRUD app (List / Add / View / Edit / Delete) for managing an NBA roster, built with HTML, Bootstrap 5, and vanilla JS.



---

## Weekly Review

**Service Topic:** NBA Roster Manager (sample data: LA Lakers)

**Data Fields:** Name, Number, Position, Height, Age, Salary, College

**List Page:** Shows Number, Name, Position, and Salary. Table on desktop, cards on mobile. Click a player to view details.

**Validation** (Add & Edit forms):
- Name — required, 2+ characters
- Number — required, 0–99
- Position — required (dropdown)
- Height — required, must match `6'9"` format
- Age — required, 18–45
- Salary — required, must be positive

`alert()`/`confirm()` confirm add, edit, and delete actions.

**RWD:** One breakpoint at 720px switches the table to cards and stacks the forms; a second at 400px shrinks the nav for small phones.

**Bootstrap:** `navbar`, `container`, `row`/`col`, `form-control`, `form-select`, `is-valid`/`is-invalid`, `btn`, `card`, `table`, `row-cols-*`, and dark mode (`data-bs-theme="dark"`).

**Problem & Solution:**
- just used sample players with in html instead of having a backend database to connect too
- Height needed a consistent format so used (`^\d'\d{1,2}"$`).

**Reflection:** 
a lot of java script coding, very similiar to CRUD in coding studio. Usage of AI for helping with Lakers theme CSS. A lot of different ways to apply css, just applying with shared was difficult because I had to think about a lot of different name tags to be applied. 

---

## File Structure

index.html      List page
add.html        Add page
view.html       View page
edit.html       Edit page
example.html    bootstrap
my.css          Shared styles

