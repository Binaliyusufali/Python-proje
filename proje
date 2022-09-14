def flatten(l):
    if type(l) is list:
        return [element for item in l for element in flatten(item)]
    else:
        return [l]

def reverse(l):
    if type(l) is list:
        return [reverse(item) for item in l[::-1]]
    return l
