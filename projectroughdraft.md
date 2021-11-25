import pandas as pd
from pulp import *
import openpyxl
import re

wb = openpyxl.Workbook()
ws = wb.active
#Then, we will be loading our fantasy player list csv into a pandas dataframe for manipulation. -

players = pd.read_csv(r"C:\Users\14789\Downloads\TeamsAtWeek_2021_sp_12_mp_12",
                     
