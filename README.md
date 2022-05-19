# Shopping List Plan

## HTML Elements

### List Page
- `ul` to which we append `li`s
- checkbox for displaying and toggling `purchased` state (w/ supabase call)
- delete all button  
  - stretch goal: individual deletions
 - `new item` button

### Create Page
 - form with `inputs` incl `qty`, `name`, `submit`
 - `submit` button creates new items and redirects to List Page
 - `back button`

## To Do  
### 1. Database Setup
- ✓ make table
- ✓ add `user_id` foreign key relation (default to `uid()`)
- ✓ add RLS `user_id = uid()` for all actions

### 2. Create Page
- add form
- write `create` function in `fetch-utils.js`
- add `submit` event listener
- grab data using `new FormData` and send to supabase
- redirect to List Page  
_validation step: New rows are appearing in supabase_

### 3. List Page: list all items
- add `ul`
- TDD `render` function (differentiate between purchased and unpurchased items)
- add `fetch` function in `fetch-utils.js`
- on load, grab data from supabase, use `render` function to display  
_validation step: sign in as another user and ensure that you're only seeing authed users' data_

### 4. List Page: delete items
- add `delete all` button in html
- add `delete all` function in fetch-utils.js
- add eventListener to call `delete` function

### 5. List Page: update items






.  
.  
.  
## copy zone  
 - `  
 - ~  
 - ✓
 - !  
 - 1  
