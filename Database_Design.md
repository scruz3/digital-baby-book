# Digital Baby Book Database Design

## Child

The Child entity stores the main information for each child.

- Child ID
- Name
- Birthday
- Age
- Profile Photo

## Milestone

The Milestone entity stores important events and achievements.

- Milestone ID
- Child ID
- Title
- Date
- Description
- Category

## Media

The Media entity stores photos and videos connected to a child or milestone.

- Media ID
- Child ID
- Milestone ID
- File Type
- File Name
- Description

## Family Member

The Family Member entity stores information about relatives connected to the child.

- Family Member ID
- Name
- Relationship
- Email

## Relationships

- One child can have many milestones.
- One child can have many photos and videos.
- One milestone can have many photos or videos.
- One child can be connected to many family members.
