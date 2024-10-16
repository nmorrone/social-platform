# DB Social Platform

//indviduo tutte le tabelle da inserire e definisco le caratteristiche

# table: POSTS
- id * PK-UNSIGNED-AI-BIGINT (NOTNULL)
- User_id FK-BIGINT (NOTNULL)
- Date DATE (NOTNULL)
- Title VARCHAR(100) (NOTNULL)
- Description TEXT (NULL)
- Media_id FK-BLOB (NULL)
- Tags VARCHAR (NULL)
- COMMENTS TEXT-FK (NULL)
- Like_id BIGINT-FK (NULL)

# table: USERS
- id * PK-UNSIGNED-AI-BIGINT (NOTNULL)
- Username CHAR (30) (NOTNULL)
- Password CHAR (25) (NOTNULL)
- Name VARCHAR (150) (NOTNULL)
- Surname VARCHAR (150) (NOTNULL)
- Birthday DATE (NOTNULL)
- Email VARCHAR(100) (NOTNULL)
- Phone CHAR(30) (NULL)

# table: LIKES
- id* PK-UNSIGNED-AI-BIGINT
- User_id FK-BIGINT (NOTNULL)
- Post_id FK-BIGINT (NOTNULL)


# table: CATEGORIES
- id * PK-UNSIGNED-AI-BIGINT
- Name CHAR (80) (NOTNULL)
- Description TEXT (NULL)
- Tag_id FK (NOTNULL)


# table: TAGS
- id* PK-UNSIGNED-AI-BIGINT
- Tag_Name VARCHAR(80) (NOTNULL)
- Category_id FK-BIGINT (NOTNULL)

# table: COMMENTS
- id* PK UNSIGNED AI BIGINT0
- Description TEXT (NOTNULL)
- Post_id FK-BIGINT (NOTNULL)
- User_id FK-BIGINT (NOTNULL)

# table: MEDIAS
- id * PK-AI-UNSIGNED-BIGINT
- User_id FK-BIGINT
- Files BLOB (NOTNULL)





