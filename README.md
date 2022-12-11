# YouTube-Video-Title-Representativeness
This is a course project studying the role of representativeness of video title in views. In our project, we investigate what would be a “good” headline that attracts viewers to click and view in the first place. En route, we analyze over 60, 000 randomly sampled non-music videos from YouTube. Specifically,
we implement both regression and DNN models. Surprisingly, we show that the representativeness of the headline to the video content (i.e., the closed caption) plays an important role in the number of views, likes, and comments. In particular, for the major 80% video samples, a 0.01 increase in representativeness would on average lead to approximately 600 more views. Therefore, video producers ought to pick representative video headlines to boost views, and in the same time, platform can generate representative scores upon producers uploading their videos for review and then encourage them to pick more representative headline choices before formally publishing videos.

## Files
- sample_data.csv: A sample data with 1000 data points since files larger than 25mb cannot be uploaded.
- Construct_Representativeness.ipynb: Use BERT to obtain embeddings for title and video closed caption to construct representiveness of titles.
- DNN_post_analysis.ipynb: Extract DNN's weights for views prediction.
- cover_feature_extracton.ipynb: utilize openCV to obtain cover image's colorfulness, RMS contrast, and saturation(highly correlated with colorfulness).
- Regression.ipynb: Linear regression to ivestigate the impact of representativeness.
