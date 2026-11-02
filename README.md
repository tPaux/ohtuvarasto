# ohtuvarastos26

<a href="https://github.com/tPaux/ohtuvarasto/actions">[![CI](https://github.com/tPaux/ohtuvarasto/actions/workflows/main.yml/badge.svg)](https://github.com/tPaux/ohtuvarasto/actions/workflows/main.yml)</a>

- name: Upload coverage reports to Codecov
    uses: codecov/codecov-action@v5
    with:
      token: ${{ secrets.CODECOV_TOKEN }}
