Klimenko Denis
==============

### Samara, Russia
### +7 (904) 749-70-22 jaschik26@yandex.ru

<br/>

## Summary

Mechanical engineer in field of railway diagnostic machinery. Develop apps for current work. My goal is position of software engineer. I like coding - coding is fun.

<br/>

## Skill highlights

* Python
* HTML/CSS/JS
* OOP (Grasp, Solid)
* Functional programming
* C
* Git
* GUI

<br/>

## Code exemples

Python

    def find_files():
        data = []
        for roots, dirs, files in os.walk(f"{server_address}"):
            for file in files:
                data.append((os.path.join(roots, file), file))
        print('done')
        return data

JS

    rollDice () {
        this.roundGain = 0
        for (let i = 0; i < 3; i++) {
            let vinSuit = this.diceSuits[Math.floor(Math.random()*this.diceSuits.length)];
            this.diceState[vinSuit] = true;
        };
        for (let suit in this.diceState) {
            console.log(this.diceState[suit]);
            console.log(this.bet[suit]);
            if (this.diceState[suit] == true) {
            this.funds += this.bet[suit] * 2;
            this.roundGain += this.bet[suit] * 2;
            };
        };
