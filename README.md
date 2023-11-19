# homework
class Student:
  def _init_(self,name,student_id,age,gender): #初始化
    self.name = name
    self.student_id = student_id
    self.age = age
    self.gender = gender
    self.grade = 0

  def set_grade(self,grade): #設定成績
    self.grade = grade
  def get_grade(self): #獲取成績
    print(grade)
  def display_student_info(self): #顯示資訊
    print("姓名{}","學號{}","年齡{}","性別{}","成績{}",sep="\n".format(self.name, self.student_id, self.age, self.gender, self.grade))
