# Cookie Cats A/B Test Analysis Project

## Overview

Cookie Cats is a hugely popular mobile puzzle game developed by Tactile Entertainment. This classic "connect three" style puzzle game requires players to connect tiles of the same color to clear the board and advance through levels. In this project, we aim to analyze the results of an A/B test that involved moving the first gate in Cookie Cats from level 30 to level 40, with a specific focus on player retention.

## Objective

Our primary objective is to assess the impact of moving the initial gate on player retention. We will employ bootstrapping techniques to repeatedly resample the dataset (with replacement) and calculate 1-day and 7-day retention for each sample. 

## A/B Test Details

- **Change**: Moving the first gate from level 30 to level 40.
- **Retention Metrics**: 1-day and 7-day player retention.

## Methodology

1. Data Resampling: We will repeatedly resample the dataset using bootstrapping.
2. Calculation of Retention Rates: For each resampled dataset, we will calculate both 1-day and 7-day retention rates.

## Key Questions

1. Did moving the first gate from level 30 to level 40 impact player retention positively or negatively?
2. How uncertain are the retention numbers in the A/B test results?

## Deliverables

1. A detailed analysis report with findings on the impact of the gate move.
2. Visualizations illustrating the distribution of retention rates.

