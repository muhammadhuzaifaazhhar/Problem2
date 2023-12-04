# Problem2
def compute_exam_stats(scores):
    total_points = sum(scores)
    average_score = total_points / len(scores)
    return total_points, average_score

last_name = input("Enter student's last name: ")
exam_scores = [float(input(f"Enter exam score {i+1}: ")) for i in range(3)]

total_points, average_score = compute_exam_stats(exam_scores)

print(f"Last Name: {last_name}")
print(f"Total Points: {total_points}")
print(f"Average Exam Score: {average_score}")
