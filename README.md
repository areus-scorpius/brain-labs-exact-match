### Additional Configuration Options:  

- **campaignNameDoesNotContain**: Exclude specific campaigns by name.  
  - Example: `["Brand", "Competitor"]` ignores all campaigns with *brand* or *competitor* in their name.  
- **campaignNameContains**: Analyze only specific campaigns.  
  - Example: `["Brand", "Generic"]` limits analysis to campaigns with *brand* or *generic* in their name.  
- **makeChanges**: Choose whether the script automatically applies negatives or just emails a review.  
- **emailAddresses**: List the emails to receive notifications.  
- **useWordInCommon**: Set to `true` to check if keywords and search queries share common words.  
- **useEditDistance**: Set to `true` and adjust **maxEditDistance** to define how many single-character changes make words distinct.  

That’s it! Test the script, schedule it, and enjoy your restored Exact Match precision. 🚀

Courtesy of: https://searchengineland.com/when-exact-match-isnt-exact-anymore-a-script-to-regain-control-307975
