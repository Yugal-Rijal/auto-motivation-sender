# auto-motivation-sender
A simple Python tool to send daily motivational messages automatically.

import random
import time

messages = [
    "You're stronger than you think.",
    "Every step you take gets you closer.",
    "Keep going. You’re doing great!",
    "Even small progress is progress.",
    "One day at a time. Never give up."
]

def send_motivation():
    message = random.choice(messages)
    print("💬 Motivational Message:", message)


for i in range(3):  
    send_motivation()
    time.sleep(5)
