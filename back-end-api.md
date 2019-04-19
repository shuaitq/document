# Back End API
## Student
### /students
* GET 获取所有学生列表
* POST 创建新的学生
### /students/id
* GET 获取学生信息
* DELETE 删除学生

## Job
### /jobs
* GET 获取所有职位列表
* POST 创建新的职位
### /jobs/id
* GET 获取职位信息
* DELETE 删除职位

## Job Skill
### /job_skills
* POST 创建新的职位技能记录
### /job_skills?job_id,skill_id
* GET 获取特定条件的职位技能记录列表
### /job_skills/id
* GET 获取职位技能记录信息
* DELETE 删除职位技能记录

## Submit Record
### /submit_record
* POST 创建新的职位提交记录
### /submit_record?student_id,job_id
* GET 获取特定条件的职位提交记录列表
### /submit_record/id
* GET 获取职位提交记录信息
* DELETE 删除职位提交记录

## Award
### /awards
* POST 创建新的奖项
### /awards?student_id
* GET 获取特定学生的奖项列表
### /awards/id
* GET 获取奖项信息
* DELETE 删除奖项

## Student Skill
### /student_skills
* POST 创建新的学生技能记录
### /student_skills?student_id,skill_id
* GET 获取特定条件的学生技能列表
### /student_skills/id
* GET 获取学生技能记录信息
* DELETE 删除学生技能记录

## Skill
### /skills
* GET 获取所有技能列表
* POST 创建新的技能
### /skills/id
* GET 获取技能信息

## Laboratory
### /laboratories
* GET 获取所有实验室列表
### /laboratories/id
* GET 获取实验室信息

## College
### /colleges
* GET 获取所有学院列表
### /colleges/id
* GET 获取学院信息

## Major
### /majors
* GET 获取所有专业列表
### /majors/id
* GET 获取专业信息
