# stored-procedures
here are the procedure for every tables in our database
Create procedure animespCHARACTER_getAll
as
begin
select *
from ANIME_CHARACTER;
end

create procedure MangaspManga_getAll
as
begin
select*
from Manga;
end

create procedure  AnimesspSHOW_getAll
as
begin
select*
from ANIME_SHOW;
end

 create procedure ANIMEspMOVIE_getAll
as
begin
select*
from ANIME_MOVIE;
end

create procedure VOICEspACTOR_getAll
as
begin
select*
FROM VOICE_ACTOR;
end

create procedure mangaspAuthor_getAll
as
begin
select*
from MANGA_AUTHOR;
end

create procedure staffspMember_getAll
    as
    begin
    select *
from STAFF_MEMBERS;
end 
