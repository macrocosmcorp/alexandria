# alexandria
A public and free repository of embeddings datasets. We're going to embed the internet. 

## Contributing
  
Here's how you can help:
  
1) Find a dataset that you want to be embedded.  
  
A good rule of thumb is making sure that the dataset is significant enough that many people will use it + isn't too insanely large to embed or too expensive/difficult to obtain + you can imagine at least one immediate tool you could build with this data.   
  
2) Download and clean a new dataset or one that's up for grabs.  
  
We'll need to remove anything that doesn't need to be embedded. Weird characters, page numbers that don't add any information to the text (chapter titles are fine), table of contents, unneeded footnotes, boilerplate text, etc.  
  
3) Convert the cleaned dataset into chunks.  
  
We'll need to split the dataset into reasonable chunks of varying size. Depending on the model that we'll use (which might change depending on subject matter, size of dataset, intended use-case, etc.), all of these chunks will have to be under some token length. If it's not a gigantic dataset (and won't need to be updated over time) it's good to assume that anything under 8000 tokens will work.  
  
How long should chunks be? How should they be split? This is somewhat confusing as it changes per dataset and per use-case. For example, if you were embedding the King James Bible, you might embed every verse individually, chunk the text into 5 verse chunks that each overlap by 2 verses, or embed every chapter as a whole. This is totally up to your best judgement. It might be one or the other, or it might be all three!   
  
4) We'll embed it for you!  
  
Once all of these steps are done, feel free to mention me or any other team member. We'll handle the process of embedding, storing, and hosting the model.  

For more questions, join our Discord server: https://discord.gg/zWa4Ay5MPb.  

## Projects

### Needs to be Sourced & Downloaded

- US Case Law
- Clinical Trials
- SEC Filings
- US Patents
- Anything you think of!

### Needs to be Cleaned

- All Hindu texts
- None yet

### Needs to be Chunked

- Coming soon

## Ready to be Embedded

- King James Bible
- Deuterocanonical books
- Apocrypha 
