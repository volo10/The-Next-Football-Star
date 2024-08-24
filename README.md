Running our project is actually very simple, it will only take a few steps:
1) Open a ipynb IDE such as Anaconda or Google Collab
2) Upload the 3 files saved in the "Datasets" directory: "players_20.csv", "players_21.csv", "players_22.csv"
3) Install the 3 packages in the first 3 cells and wait till finishes: "optuna", "pytorch-tabnet", "catboost"
4) Every cell has a documation with it's functionallity:
   * The first cell is the only one that you have to run in order for othr to work, it includes a helper function to handle the datasets "fillna_avg_adjacent_rows"
   * The next 3 cells shows the use of Optuna: the #5 cell shows performance pre-optuna, the #6 cell activates it, the #7 cell shows performance after optuna
   * The next 2 cells show the comparison between models for both potential (cell #8 potential,  cell #9 market value)
   * the next 5 cells show the trial and error + optuna trial to ding the best MLP architectue (cell # 10 + #12-14 are trial and error and cell #11 is optuna)
   * the next 3 cellsshow the 500 epochs comparison between CAN (cell #15), CNN (cell #16), MLP (cell #17)
   * the last 2 cells show the finals results for the best MLP for 3500 epochs, for potential (cell #18) and market value (cell #19)
5) In the repo you can find a detailed report, explaining our work and a ppt presentation that sums up the work from the report.
