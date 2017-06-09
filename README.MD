```
const site = {
    header: {
        name: "Harry Merzin",
        description: "Hi, I'm Harry. I'm a high schooler/ software engineer from New York. I ❤️ everything JavaScript and Swift. I focus a lot on open source Node ⬢, React ⚛️, Swift 🐦 and JavaScript 💛. I also enjoy writing and writing about TypeScript 💙.",
        github: 'http://github.com/hmerzin',
        twitter: 'http://twitter.com/harrymerzin',
        facebook: 'http://facebook.com/harry.merzin'
    },

    sections: [
        {
            title: 'My Writing 📝', //'GitHub 🐙',

            items: [
                //{type: 'link', value: 'http://github.com/hmerzin', text: 'mah github'}
                { type: 'link', value: 'https://dev.to/harry/typescript-head-first', text: 'My article on TypeScript' },
                { type: 'plain', value: 'I love to write about all sorts of technologies. This is an in-depth article I wrote about beginning TypeScript from JavaScript.' },
                { type: 'link', value: 'https://github.com/hmerzin/learning-core-data', text: 'My tutorial on iOS data persistance with Core Data.' },
                { type: 'plain', value: 'This tutorial was used to help my fellow iOS Nanodegree students learn the Core Data framework, as some of the course material was tricky.' }
            ]
        },

        {
            title: 'My Work 👨‍💻',

            items: [
                { type: 'link', value: 'https://www.flickr.com/photos/nnsanews/albums/72157675976588370', text: 'My work for the National Nuclear Security Agency' },
                { type: 'plain', value: 'I wrote and packaged all of the software on the screens on the stage behind the speakers. Each wall was its own app, and was fully interactive throught the touch screens.' },
                { type: 'plain', value: 'I also currently work with a company called Lapin, to create a software and hardware ecosystem to ensure that gyms are as fit as their members.' }
            ]
        }
    ]

};

export default site;
```
