# DB Social Platform

//indviduo tutte le tabelle da inserire e definisco le caratteristiche

# table: POSTS
- id * PK UNSIGNED AI BIGINT
- User_id FK BIGINT
- Date DATE
- Title VARCHAR()
- Description SMALL TEXT
- Media_id FK
- Tags
- Comments
- Like_id BIGINT FK

# table: USERS
- id * PK UNSIGNED AI BIGINT
- Username
- Password
- Name
- Surname
- Birthday
- Email
- Phone

# table: LIKES
- id* PK  UNSIGNED AI BIGINT
- User_id FK BIGINT
- Post_id FK BIGINT


# table: CATEGORIES
- id * PK UNSIGNED AI BIGINT
- Name
- Description
- Tag_id FK


# table: TAGS
- id* PK UNSIGNED AI BIGINT
- Tag_Name
- Category_id 

# table: COMMENTS
- id* PK UNSIGNED AI BIGINT0
- Description
- Post_id
- User_id

# table: MEDIAS
- id * PK BIGINT
- User_id FK BIGINT
- Description





