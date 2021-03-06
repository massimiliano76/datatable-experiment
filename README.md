# Datatable experiment

Experimenting w/ highly opionated datatable design.

The basic idea is to provide feature-complete and super flexible set of primitive components that allow you to easily put together a fully customised datatable componen that you can very easily reuse and modify within your project.

Note: this is not intended as a final product but an experiment. Hence, the code and organisation is geared towards practicality, not purity.

## Design goals

- Fully responsive, mobile-first (ability to )
- Fully customizable markup
- Work fluently for both client and backend data
- Customizable filters
- Customizable search
- Easily humanizable (nice labels, etc)

## Project Status

- Started: Basic API design
- Started: Basic base components

## Project setup

Install dependencies:

```
yarn
```

Run development server:

```
yarn dev
```

## ToDo

- [ ] Filtering based on boolean
- [ ] Filtering based on string (equal)
- [ ] Filtering based on date (equal, smaller, greater)
- [ ] Filtering based on number (equal, smaller, greater)
- [ ] Sorting by date
- [ ] Search
- [x] Add window resize observer that watches Tailwind breakpoints and stores current breakpoint in state. (We can then use it for programatically reshape the table based on user configuration.)
