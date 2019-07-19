# Pointmade

Thanks for your interest in a developer role at Proofpoint Security Awareness
Training! This repo contains a toy version, implemented in [Rails
5.2](https://guides.rubyonrails.org/v5.2/) and [Ember
3.8](https://api.emberjs.com/ember/3.8), of our real product. Its purpose is
to help simulate "real work" as much as possible within the constraints of our
interview process. Please
[duplicate](https://help.github.com/en/articles/duplicating-a-repository) this
repo to a :lock: **private** repository, and add the Proofpoint hiring manager
you are communicating with as a collaborator. Then watch for your first
interview task as a GitHub issue.

In the mean time, read on for how to set up the project locally ...

* `git clone git@github.com:{{your-username}}/pointmade.git` &larr; your private repo
* `cd pointmade`


## Frontend

### Prerequisites

* [Node.js](https://nodejs.org/) (with npm)

### Installation

```
cd frontend
npm install
```

### Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Running Tests

* `ember test`
* `ember test --server`

### Success

![Pointmade frontend](./frontend/success.png)


## Backend

### Prerequisites

* [rbenv](https://github.com/rbenv/rbenv)


### Installation

```
cd backend/
rbenv install
export PATH="./.gems/bin:$PATH"
export GEM_PATH="./.gems"
export GEM_HOME="./.gems"
gem install bundler --version '~> 2.0.0'
bundle install
```

### Running / Development

* `rails s`
* Visit your app at [http://localhost:3000](http://localhost:3000).

### Running Tests

* `rails test`

### Success

![Pointmade backend](./backend/success.png)


# Legal

Ember's and Rails's scaffolding is used under the MIT license.

The remainder is copyright &copy; Proofpoint, Inc. All rights reserved.
