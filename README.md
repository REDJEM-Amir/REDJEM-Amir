<h2>👋 Hello, I'm Amir</h2>

<h3>👨‍💻 Front-end Developer</h3>

```javascript
import React, { useState } from "react";

export default function AboutMe() {
  const [languages, setLanguages] = useState([
    "javascript",
    "typescript",
    "html",
    "scss",
  ]);
  const [tools, setTools] = useState([
    "redux",
    "reactjs",
    "jest",
    "react-testing-library",
  ]);
  const [devOps, setDevOps] = useState(["github-actions", "docker"]);
  const [methods, setMethods] = useState(["scrum", "tdd"]);

  return null;
}
``` 
