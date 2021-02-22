# Advanced NLP with Spacy 

## Chapter 1
- Creating nlp object
  - The first step is to create an nlp object
  ![nlp_object](images/nlp_object.png)
  
- Tokens and span
  - Tokens are the characters inside the nlp object 
  - Token are accessed by using index - doc[0]
  - Span are accessed by using slices - doc[2:5]
   ![token_and_span](images/tokens_and_span.png)
   
- Attributes of token
  - There are many built in function that can be used on tokens
    ![Attributes of token](images/attributes_of_token.png)
    
- Using Statistical models
   - Loading statistical model
      ![loading_stats_model](images/loading_stats_model.png)
   - Pos tagging using stats model
      ![pos_tagging](images/stats_model_pos.png)
    - Entity recognition using stats model
      ![Entity recognition](images/stats_model_entity.png)
   
 - Matching patterns
  - Spacy matcher is better then using regex because it allows much complex search, we can even search for verbs, 
   
