if __name__ == '__main__':
    n = int(input())
    student_marks = {}
    for _ in range(n):
        name, *line = input().split()
        scores = list(map(float, line))
        student_marks[name] = scores
    query_name = input()
    for i in student_marks:
        if i==query_name:
            result=student_marks.get(i)
            print(f"{sum(result)/3:.2f}")
            
           
    
