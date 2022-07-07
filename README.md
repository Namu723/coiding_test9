#문자열 내 마음대로 정렬하기


def solution(strings, n):
    answer = []

    return sorted(strings, key=lambda x: (x[n], x))


#print(solution(["abce", "abcd", "cdx"]	, 2))
