# A-robust-registration-loss
Deep learning, rigid registration, intersected lines, unsupervised learning
{r image-ref-for-in-text, echo = FALSE, message=FALSE, fig.align='center', fig.cap='Some cool caption', out.width='0.75\linewidth', fig.pos='H'}
knitr::include_graphics("./data/introduce_our_loss.pdf")
- Data prepartions
You can generate your own datasets by this.
- Data
Your download the [Human dataset](), [Airplane datasets](), [Real dataset]()
- Loss
Our metrics have different versions from the beginning of the discussion. The overall research route is from grid data to general point cloud data. The specific loss form can refer to [loss.py]()
- Experiments
  - Optimization of a single example by embedding the metric into the traditional optimization based on gradient descent.[Exp1]()
  - Embed our metrics into deep learning and transform supervised frameworks into unsupervised frameworks,([RMP-Net](), [DCP](), [FMR]()).[Exp2]()
- visualize point cloud tools
Our visualized was implemented with Keyshot, we provide some scripts to help point cloud rendering.[scirpts]()
- Acknowledgement
