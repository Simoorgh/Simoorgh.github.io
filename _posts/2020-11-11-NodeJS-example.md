---
published: true
---
## some nodejs example
NodeJS:

only 1 backtick

`
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
`


only 2 backtick

``
const express = require('express')
const app = express()
const port = 3000

app.get('/', (req, res) => {
  res.send('Hello World!')
})

app.listen(port, () => {
  console.log(`Example app listening at http://localhost:${port}`)
})
``



backtick + tab


`
  const express = require('express')
  const app = express()
  const port = 3000

  app.get('/', (req, res) => {
    res.send('Hello World!')
  })

  app.listen(port, () => {
    console.log(`Example app listening at http://localhost:${port}`)
  })
`


only tab:


  const express = require('express')
  const app = express()
  const port = 3000

  app.get('/', (req, res) => {
    res.send('Hello World!')
  })

  app.listen(port, () => {
    console.log(`Example app listening at http://localhost:${port}`)
  })




only 3 spaces:


   const express = require('express')
   const app = express()
   const port = 3000
   
   app.get('/', (req, res) => {
      res.send('Hello World!')
   })

   app.listen(port, () => {
      console.log(`Example app listening at http://localhost:${port}`)
   })