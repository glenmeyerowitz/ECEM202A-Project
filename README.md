## Generative Adversarial Networks to Mitigate Failures of Embedded Sensors

Embedded sensors are becoming more and more common. This ubiquity also increases their use in safety critical applications, such as autonomous vehicles or aerospace applications. If a sensor experiences a failure, or if the signal from the sensor degrades, it is necessary for the system to respond appropriately and adjust its behavior. Generative Adversarial Networks (GANs) are a tool used to train Neural Networks (NNs) by allowing these two NNs to "compete." This technique has never been applied to embedded sensors to increase their robustness against common failure modes and degradations.

This project will work to train an embedded system to respond to weather related degradations, such as rain, dust, and snow by using GANs. In this way, a system can react to an environment that it may have never experienced or been directly trained on. The system will develop a "degradation factor" (DF) to evaluate how trustworthy any given sensor input is based on the level of degradation that the sensor is experiencing. 

Depending on the DF that the system estimates, the system may need to enter a degraded state. For instance, if the system is an autonomous vehicle and there is a safety critical camera that is experiencing a high DF, the system may decrease its maximal operating speed and increase the following distance to other vehicles. This is a safety measure to mitigate the impact of a degradation on system safety.

### Contact Us

If you have any questions or want to reach out to discuss this project, you can reach [Glen Meyerowitz](https://glenmeyerowitz.com) on [Twitter](https://twitter.com/GlenMeyerowitz) or by [email](mailto:gmeyerowitz@ucla.edu).
