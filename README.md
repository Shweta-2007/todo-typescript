# TYPESCRIPT-TODO

- npm init -y
- npm install typescript --save-dev
- npx tsc --init
- Bundler: snowpack
- npx create-snowpack-app . --template @snowpack/app-template-blank-typescript --force
- npm start
- npm i --save-dev @types/uuid
- npm start
- This is javascript code:

function verify(result) {
if (result === "pass") {
console.log("Passed")
} else {
console.log("Failed")
}
}

- This is typescript code:

type Result = "pass" | "fail"

function verify(result: Result) {
if (result === "pass") {
console.log("Passed")
} else {
console.log("Failed")
}
}

- Another example:

const user = {
name: "Hayes",
id: 0,
};

interface User {
name: string;
id: number;
}

const user: User = {
name: "Hayes",
id: 0,
};
