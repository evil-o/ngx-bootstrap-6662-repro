This reproduces ngx-bootstrap issue [6662](https://github.com/valor-software/ngx-bootstrap/issues/6662).

Changes done to the generated code reproduce the issue:
- Create a new angular app with ng new
- Add ngx-bootstrap
- Update main.ts to switch to `bootstrapModule`

To see the issue:
1. Check out the repository
2. Install deps using npm i
3. Run npm start in the project root