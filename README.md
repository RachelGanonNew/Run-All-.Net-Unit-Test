<h3 align="center">Run All .Net Unit Test</h3>
<p align="center">This is an action to run all unit test files that end with '*.Tests.dll' in the repository.<p>

## Usage

This GitHub Action lets a user to run all the unit test solution in the ${{ github_workspace }} path autometically.


## Setup
  
```yaml
# .github/workflows/take.yml 
    steps:
    - name: unit test
      uses: RachelGanonNew/Run-All-.Net-Unit-Test@main
```

