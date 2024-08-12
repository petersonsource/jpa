# jpa

http://localhost:8080/bookstore/books

{
    "title": "Domain Driven Design",
    "publisherId": "c97d5634-02b2-4c5c-82d7-7f6b0147e535",
    "authorIds": ["5c57ae2f-5ad6-4d42-8cce-a73879ea3a27"],
    "reviewComment": "That is a review comment"
}

insert into tb_publisher values (gen_random_uuid(), 'Alta Books');
insert into tb_publisher values (gen_random_uuid(), 'Pearson');

select * from tb_publisher;

insert into tb_author values (gen_random_uuid(), 'Eric Evans');
insert into tb_author values (gen_random_uuid(), 'Paul Deitel');
insert into tb_author values (gen_random_uuid(), 'Harvey Deitel');

select * from tb_author;
select * from tb_book;
select * from tb_book_author;
select * from tb_review;
