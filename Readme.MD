# Age GAN

This repository provides an implementationg of the Conditional GAN Architechture to peform Age editting. We use the UTK Face Dataset to achieve this task, and it needs to be added to the root repository.

## Conditional GAN Architechure

The diagram below shows the original Conditional Generative Adversarial Networks Architechture.
![Conditional GAN architechture](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/ConditionGAN/cGAN_overview.jpg "Conditional GAN architechture")

## Proposed Architechure

The diagram below shows the achitechure proposed by us for the task.
![AgeGAN architechture](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/proposedmodel.png "AgeGAN architechture")

## Generator-Discriminator Architechture

The diagram below shows the generator-discriminator achitechure.
![Generator](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/generator.png "Generator architechture") | ![Discriminator](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/discriminator.png "Discriminator architechture")

## Loss Curve

The diagram below shows the loss curve for the generator and the discriminator

![Loss Curve](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Loss/loss.png "Loss Curve")

## Examples

Example 1

![Man Real Age 80](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/age80-real.png "Man-Real Age 80") | ![Man Fake Age 5](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/age5-real.png "Man-Fake Age 5")

Example 2

![Woman Real Age 30](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/real30.png "Woman-Real Age 30") | ![Woman Fake Age 80](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/fake30.png "Woman-Fake Age 80")
