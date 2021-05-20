# Age GAN

This repository provides an implementationg of the Conditional GAN Architechture to peform Age editting. We use the UTK Face Dataset to achieve this task, and it needs to be added to the root repository.

## Conditional GAN Architechure

The diagram below shows the original Conditional Generative Adversarial Networks Architechture.
![Conditional GAN architechture](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/ConditionGAN/cGAN_overview.jpg "Conditional GAN architechture")

## Proposed Architechure

The diagram below shows the achitechure proposed by us for the task.
![AgeGAN architechture](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/proposedmodel.png "AgeGAN architechture")

## Generator Architechture

The diagram below shows the generator achitechure.
![Generator](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/generator.png "Generator architechture")

## Discriminator Architechture

The diagram below shows the discriminator achitechure.
![Discriminator](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Proposed%20Model/discriminator.png "Discriminator architechture")

## Loss Curve

The diagram below shows the loss curve for the generator and the discriminator

![Loss Curve](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/Loss/loss.png "Loss Curve")

## Examples

Example 1

Age changes from 80 to 5.

![Man Real Age 80](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/age80-real.png "Man-Real Age 80") ![Man Fake Age 5](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/age5-real.png "Man-Fake Age 5")

Example 2

Age changes from 30 to 80.

![Woman Real Age 30](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/real30.png "Woman-Real Age 30") | ![Woman Fake Age 80](https://github.com/rishabhsahlot/AgeGAN/blob/AgeGANFirstTag/images/examples/fake30.png "Woman-Fake Age 80")
