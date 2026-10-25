import random

def generate_story():
    stories = [
        {
            "title": "The Magical Rabbit",
            "story": "Once upon a time, a rabbit found a magical carrot in a forest. It shared the carrot with its friends. Everyone became happy. The rabbit learned that sharing is caring."
        },
        {
            "title": "The Brave Little Bird",
            "story": "A little bird was afraid to fly. One day, it tried its best and flew across the garden. Its friends cheered happily. The bird learned to be brave."
        },
        {
            "title": "The Friendly Dragon",
            "story": "A little dragon lived near a village. Everyone was afraid of him. One day, he helped a lost child. The villagers became his friends. The dragon learned that kindness creates friendship."
        }
    ]

    selected_story = random.choice(stories)

    print("\n" + "=" * 40)
    print(" AI CHILDREN'S STORY GENERATOR ")
    print("=" * 40)
    print("\nTitle:", selected_story["title"])
    print("\nStory:", selected_story["story"])
    print("\nMoral: Always be kind and helpful!")
    print("=" * 40)

generate_story()
