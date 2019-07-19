To prepare for website:

1. Edit document & compile w/ XeLaTeX
2. Navigate in cmd to folder, enter the following in cmd:
	pdfcrop schedule.pdf
3. Convert to svg format by entering following in cmd:
	pdftocairo -svg schedule-crop.pdf

	OR

	Convert to png format by replacing -svg above with -png