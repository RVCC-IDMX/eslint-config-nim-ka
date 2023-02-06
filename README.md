# Alex's Awesome Assignment

## Let's Learn an ESLint Rule

The `semi` rule in ESLint controls whether automatic semicolon insertion (ASI) is allowed. ASI is a feature of JS where the engine inserts semicolons automatically at newlines to break up invalid statements, allowing you to elide semicolons in your code and instead let the engine place them for you. ASI as a language feature is controversial, because although it arguably allows for cleaner code, its behavior is occasionally unintuitive and can lead to bugs. To help this, ESLint provides the `semi` rule, which can be used to enforce your preferences towards ASI. You can either require code to always place semicolons explicitly, or to never do so.

[Link to doc page](https://eslint.org/docs/latest/rules/semi)