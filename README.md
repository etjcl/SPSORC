# SPSORC

## Experiment Structure

- **6 Latin Square Lists**: Each participant sees one of 6 lists, automatically assigned based on the counter
- **58 items per list**: 
  - 34 filler items
  - 24 experimental items (covering 6 conditions across 24 item sets)
- **3 practice items**: Introduction to the task format
- **Self-paced reading**: Participants read sentences word-by-word by pressing the space bar
- **Comprehension questions**: After each sentence, participants answer Yes/No comprehension questions

## Conditions

The experimental items test 6 conditions:
1. `subj_extractedPP` - Subject extraction with extracted PP
2. `subj_noextract:coordination:` - Subject, no extraction, coordination
3. `subj_ungrammatical :que` - Subject, ungrammatical with que
4. `obj_extractedPP` - Object extraction with extracted PP
5. `obj_noextract:coordination` - Object, no extraction, coordination
6. `obj_ungrammatical:que` - Object, ungrammatical with que

## Files

- `experiment.html` - Main experiment file (load this in IbexFarm or locally)
- `data_includes/experiment_data.js` - All experimental items, fillers, and Latin square logic
- `chunk_includes/intro_spanish.html` - Spanish consent form and participant information
- `Experiment_Latin_Square_Lists.xlsx` - Source data with all 6 lists

