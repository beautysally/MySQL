# MySQL
-- 1  
SELECT * FROM dept;
-- 2
SELECT  EMPNO,ENAME, JOB , HIREDATE FROM emp;
-- 3
SELECT distinct JOB FROM emp;
-- 4
SELECT EMPNO"Employee",ENAME "Emp#",JOB,HIREDATE"Hire Date" FROM emp ;
-- 5
SELECT concat (ENAME," ", ",",JOB)"Employee and Title"FROM emp;
