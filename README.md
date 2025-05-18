#practice in a code that accepts a string and returns a dictionary
def char_frequency(s):
    freq = { }
    for char in s:
        if char in freq:
            freq[char] +=1
        else:
            freq[char] = 1
    return freq
print(char_frequency("honolulu"))
