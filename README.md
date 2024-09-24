Developed a predictive model to determine who would have survived the Titanic.

## About the dataset

The tragedy stands out in history as one of the deadliest commercial maritime disasters during peacetime.
More than half of the passengers and crew died, due in large part to poor safety standards, such as not having enough lifeboats or not ensuring all lifeboats were filled to capacity during evacuation.

This dataset presents the most up-to-date knowledge about the passengers that were on the *Titanic*, including whether or not they survived. The dataset was downloaded from Kaggle.com and has already been split into a training set (in the `train.csv` file) and test set (in the `train.csv` file).

The dataset contains the following variables:

| Variable    | Description                                                           |
| :-----------| :-------------------------------------------------------------------- |
| `PassengerId`    | A unique number identifying each passenger.                          |
| `Survived`  | Whether this passenger survived (0 = No; 1 = Yes). (This variable is not present in the test dataset file.)                     |
| `Pclass`    | Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)                           |
| `Name`      | Name                                                                  |
| `Sex`       | Sex                                                                   |
| `Age`       | Age                                                                   |
| `SibSp`     | Number of Siblings or Spouses Aboard                                     |
| `Parch`     | Number of Parents or Children Aboard                                     |
| `Ticket`    | Ticket Number                                                         |
| `Fare`      | Passenger Fare (British pound)                                        |
| `Cabin`     | Cabin                                                                 |
| `Embarked`  | Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)  |


| Label        | Definition                                                                   |
| :----------- | :--------------------------------------------------------------------        |
| Sibling      | Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic      |
| Spouse       | Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances Ignored) |
| Parent       | Mother or Father of Passenger Aboard Titanic                                 |
| Child        | Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic          |

