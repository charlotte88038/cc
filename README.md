# cc
import random

def generate_random_list(length, min_value, max_value):
    random_list = [random.randint(min_value, max_value) for _ in range(length)]
    return random_list

def calculate_mean(input_list):
    mean = sum(input_list) / len(input_list)
    return mean

length = 10
min_value = 1
max_value = 100

random_list = generate_random_list(length, min_value, max_value)
print("随机生成的列表：", random_list)

mean = calculate_mean(random_list)
print("列表的平均值：", mean)
