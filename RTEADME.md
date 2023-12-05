* 

- SELECT * FROM `students` WHERE `date_of_birth` LIKE '1990-%';

- SELECT * FROM `courses` WHERE `cfu` > '10';

- SELECT * ,TIMESTAMPDIFF(YEAR,`date_of_birth`,CURDATE()) as `anni` FROM `students` WHERE TIMESTAMPDIFF(YEAR,`date_of_birth`,CURDATE()) > 30;

- SELECT * FROM `courses` WHERE `period` LIKE 'I %' AND `year` LIKE '1';

- SELECT * FROM `exams` WHERE `date` LIKE '2020-06-20' AND `hour` > '14:00';

- SELECT * FROM `degrees` WHERE `level` LIKE 'magistrale';

- SELECT COUNT(*) FROM `departments`;

- SELECT * FROM `teachers` WHERE `phone` IS NULL;