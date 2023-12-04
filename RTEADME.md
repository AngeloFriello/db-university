* 

- SELECT * FROM `students` WHERE `date_of_birth` LIKE '1990-%';

- SELECT * FROM `courses` WHERE `cfu` > '10';

- SELECT * FROM `students` WHERE `date_of_birth` BETWEEN '1800-01-01' AND '1993-12-04';

- SELECT * FROM `courses` WHERE `period` LIKE 'I %' AND `year` LIKE '1';

- SELECT * FROM `exams` WHERE `date` LIKE '2020-06-20' AND `hour` > '14:00';

- SELECT * FROM `degrees` WHERE `level` LIKE 'magistrale';

- SELECT COUNT(*) FROM `departments`;

- SELECT * FROM `teachers` WHERE `phone` IS NULL;