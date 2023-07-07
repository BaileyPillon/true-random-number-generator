def generate_true_random_number():
    response = requests.get('https://www.random.org/integers/?num=1&min=0&max=999999999&col=1&base=10&format=plain&rnd=new')
    number = int(response.text.strip())
    return number
