

# Getting started
The project link is : [https://www.instructables.com/id/COVID-19-Rapid-Manufacture-Ventilator-BVM-Ambubag-/](https://www.instructables.com/id/COVID-19-Rapid-Manufacture-Ventilator-BVM-Ambubag-/)
The repo  with this documentation can be downloaded here: 
The USP(Unique Selling Proposition) of this design is how easy and fast it can scale for mass production for the following reasons:

- Automated production: The production of each part is fully automated (laser cutting), with only 8 different parts
- Only 6 off-the-shelf components: Very few different components are needed and no exotic parts are needed (not even a motor coupling)
- Simple mechanism: It uses a super simple mechanism with just an arm mounted to a motor - no complicated mechanisms to go wrong, just one moving part
- Fast assembly: Complete assembly is possible in around 20 min with one person
- Adjustable settings: Has full adjustment of breath frequency and pressure/tidal volume and with a small adaption can function within all NHS requirements
- Low cost

See it here: [https://youtu.be/jutBw_xIwTw](https://youtu.be/jutBw_xIwTw)

# Disclaimer 

I'm not selling this product, just releasing the design as open source to help others. 

**This design doesn't currently meet the NHS requirements (in link below) and does not have medical product approval which will be needed for treatment**. 
A list of improvements for the next version with the aim of meeting the NHS spec is kept in the GitHub readme (link below), some of those things are here:

- A 12V battery backup with at least 20 min run time
- A battery management circuit to automatically switch over to the battery in a power cut (not actually required but would seem sensible)
- A pressure sensor alarm for sensing failure and a buzzer & LED to create an alarm on failure
- An LCD screen to show pressure and other values and Settings
GitHub code link: [https://github.com/RealFreshRate/OpenVent](https://github.com/RealFreshRate/OpenVent)

NHS Rapidly manufactured ventilator system specification: [https://www.gov.uk/government/publications/specification-for-ventilators-to-be-used-in-uk-hospitals-during-the-coronavirus-covid-19-outbreak](https://www.gov.uk/government/publications/specification-for-ventilators-to-be-used-in-uk-hospitals-during-the-coronavirus-covid-19-outbreak)


- All users of this design and device shall be deemed notified of the warnings stated herein. 
- This device is a simply designed, fast produced ventilator. This device should not be used in place of an existing hospital ventilator. 
- These should only be used as a last resort where a patient has no other alternative due to the lack of availability of existing ventilators. 
- **This is not a fully medically certified device and should not be relied upon as such. The device is designed for use by trained medical professionals and should only be used by trained medical professionals; it is not intended for home use.**
- The designers and manufacturers of this device shall not be held liable for any death or injury that may result from this device.
- The designers and manufacturers of this device give no guarantees or warranties as to the efficacy and/or safety of this device.
- This design isn't connected with dyson or any other ventilator projects including Dyson CoVent.

# Problem statement

Ventilation is the only known available treatment for sufferers of COVID-19. 
Existing ventilation machines in hospitals are complex general purpose machines costing £10s of thousands. The availability of the existing ventilators is no where near enough to meet the predicted required numbers, for example in the UK around 5000 ventilators currently exist within the NHS but it is predicted they will need around 30,000 in just a few weeks. Critically ill patients left without ventilation treatment are in danger of losing their life.

As far as I understand, one effect of the virus as well as damaging the lungs, it also produces a very sticky mucus in the lungs which causes the lungs to collapse and makes it very difficult for the patent to breath of their own accord. Ventilation can be delivered either via intubation or a well sealed mask and delivers continuous positive air pressure into the lungs to keep them inflated at all times. Conscious less ill patents can be aided using a CPAP (Continuous Positive Airway Pressure) ventilation device like a sleep apnea device, this delivers a constant air of the same flow rate and pressure. The more critically ill patients need a machine to breath for them which varies the pressure and flow according to inhale and exhale and relies on maintaining a good seal and a PEEP valve to keep the lungs continually inflated.

An analogy: Imagine inflating a balloon, letting it deflate completely, then re-inflating it, that is like CPAP. If you inflated the balloon, deflated it half way, then re-inflated it, that's more like the treatment needed for the worse sufferers.

**The aim is:**

1. for a very simple low cost design

2. made using readily available components

3. that can be manufactured quickly and easily in small quantities or on mass at low cost

4. to work reliably and with the lowest risk to the patient (partly to help speed up the medical product approval process, if this project gets that far)


# Design

This design is based on a hand operated BVM (Bag Valve Mask) or known as ambu bag, which when combined with a PEEP valve will meet most of the NHS requirements for COVID-19 ventilation treatment. My design replaces the hand making this automated.

# Credits:

Credit to the people below for helping to make this all possible:

Sam Reilly - Software Certification Engineer
Sadie - ITU nurse
Tom Breddal
Consultant Anesthetist in UK ITU