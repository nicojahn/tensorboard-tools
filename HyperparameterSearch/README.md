# Utilizing the hyper parameter utility of tensorboard
 * Currently in mix with numpy (logspace) for the learning rate
  * Can be extended to random search or tensorboards scaling/spacing
 * Currently only grid searching for epochs and learning rate
 * But with a lot of metrics, which do fit also for inbalanced datasets
 * Planning to calculate the mean of those metrics over n repetitions
 * Planning to adapt it to pytorch/other ml frameworks
