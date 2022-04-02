Aliaksei Kachkin
Contacts: e-mail: lex6164665@gmail.com
          phone : +375 (33) 674-07-15

About me: I'm a Math teacher. My goal is to become a Front-end developer. I like to spend time reading books and finding out the diffcult tasks. I'm very calm.

Skills: HTML, CSS, Git.

Code example:
    Run-length encoding
    const runLengthEncoding = (str) => {
    const result = []
    if (str) {
    let current = str[0]
    let counter = 1 
    for ( let i = 1; i < str.length; ++i) {
        if (str[i] === current) {
        counter +=1
        } else {
        result.push([counter, current])
        current = str[i]
        counter = 1
        }
    }
    result.push([counter, current])
    }
    return result
    }

Education: Information systems software

Level of English: A2