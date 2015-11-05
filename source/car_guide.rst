How to assemble your Freescale Cup car
======================================

The car provided to you requires some assembly before you're able to properly use it in the competition. In particular, you will need to add the servo, the FRDM-KL25Z board and the camera, on a custom made mount.

Please note that this document is meant only to guide you and presents only one way to build everything together. If you are so inclined, feel free to change things as you like, especially for the board and camera mount. However, do keep in mind that:

* You will need to connect the camera, servo and battery pack to the FRDM-KL25Z board;
* All the components should be tightly fitted to the car so they won't get thrown off during the actual race.

Inventory
---------

.. figure:: Pictures/03-01Components.jpg
   :alt: The items you are given
   :name: fig:comp_init

The big box you are given should have the same contents as :numref:`fig:comp_init`: another smaller box, containing the car and more, the camera board, the camera lens and some cables, the servo, the FRDM-KL25Z board and a USB cable.

.. figure:: Pictures/03-02Components2.jpg
   :alt: Contents of small box
   :name: fig:comp_init_car

The contents of the smaller box are the actual car, a bag with screws, nuts and more and a second bag with pieces to help you assemble your car. The screwdriver is not included, but you will need it to get everything together.

Installing the servo
--------------------

The first step is installing the servo. This process is more or less set in stone, but there are certain points where you can get creative.

First, take out the servo and the four yellow plastic pieces presented in :numref:`fig:serv_comps`.

.. figure:: Pictures/03-03ServoComponents.jpg
   :alt: Components to start off with
   :name: fig:serv_comps

Then, combine the yellow parts as below:

.. figure:: Pictures/03-04ServoYellow.jpg
   :alt: Combined yellow parts

Unscrew the black connector from the servo and replace it with the yellow one you just made. Use the same screw and remember to add in the small yellow piece to fasten everything together.

.. figure:: Pictures/03-05ServoDisassemble.jpg
   :alt: Disassembled servo

.. figure:: Pictures/03-06ServoReplaced.jpg
   :alt: Servo gear replaced

The next step is to assemble the axles connecting the servo to the wheels. The pieces you need are shown in :numref:`fig:axle_pieces` and the expected result is in :numref:`fig:axle_assemble`.

.. figure:: Pictures/03-07AxlePieces.jpg
   :alt: Axle pieces
   :name: fig:axle_pieces

.. figure:: Pictures/03-08AxleAssemble.jpg
   :alt: Assembled axles
   :name: fig:axle_assemble

We also need to insert the bearings in the open end of the axles, as shown in :numref:`fig:axle_bearings`.

.. figure:: Pictures/03-09AxleBearings.jpg
   :alt: Assembled axles with bearings
   :name: fig:axle_bearings

Once we have our assembled axles, we need to assemble them with the servo. For this, we use two screws and two nuts to fasten them.

.. figure:: Pictures/03-10ServoAxlesElements.jpg
   :alt: Components needed to assemble axels to servo
   :name: fig:servo_axle_comps

.. figure:: Pictures/03-11ServoAxlesAssemble.jpg
   :alt: Servo with the axles attached
   :name: fig:servo_axle_attach

The last step is to actually put the servo on the car. Gather the items from :numref:`fig:servo_car_comps`, add the plastic blocks to the servo block (:numref:`fig:servo_car_blocks`), then insert the servo in its slot, towards the front of the car (:numref:`fig:servo_car_insert`). Finally, fasten it in place with screws on the underside of the car (:numref:`fig:servo_car_bottom`).

.. figure:: Pictures/03-12ServoCarComps.jpg
   :alt: Pieces required to attach servo to car
   :name: fig:servo_car_comps

.. figure:: Pictures/03-13ServoCarBlocks.jpg
   :alt: Attaching plastic blocks to servo
   :name: fig:servo_car_blocks

.. figure:: Pictures/03-14ServoCarInsert.jpg
   :alt: Inserted servo
   :name: fig:servo_car_insert

.. figure:: Pictures/03-15ServoCarBottom.jpg
   :alt: Bottom of the car with servo screws
   :name: fig:servo_car_bottom

Installing the FRDM-KL25Z board
-------------------------------

You can choose to put the board anywhere you wish, but there are certain important considerations you need to keep in mind:

* the battery block, the camera and the servo have cables that must be inserted into the board;
* it is very *important* that you insert the cables correctly; inserting them the wrong way can short-circuit your car board;
* the board itself should be fitted firmly, so it cannot be thrown off during the actual race.

You can see an example in :numref:`fig:board_fitted`. This particular method is not great, as the board is wobbly, possibly affecting the car's balance during the race. However, the position should be reached by all the cables and it is secured to the car.

.. figure:: Pictures/03-16BoardFitted.jpg
   :alt: FRDM board fitted to the car
   :name: fig:board_fitted

:numref:`fig:cabling_battery` and :numref:`fig:cabling_front` show you how the cables from the battery block (first picture), camera and servo (second picture) should be inserted. However, we suggest you ask an expert, if available, to ensure everything is fine. As we said, putting them in the wrong way can lead to short-circuiting your board and is very dangerous.

.. figure:: Pictures/03-17CablingBattery.jpg
   :alt: Battery cables
   :name: fig:cabling_battery

.. figure:: Pictures/03-18CablingFront.jpg
   :alt: Camera and servo cables
   :name: fig:cabling_front

Putting together the camera and building a mount
------------------------------------------------

The first part is fairly straight-forward: screw the camera lens and the sensor together (:numref:`fig:camera_parts` and :numref:`fig:camera_assemble`).

.. figure:: Pictures/03-19CameraParts.jpg
   :alt: Camera parts
   :name: fig:camera_parts

.. figure:: Pictures/03-20CameraAssemble.jpg
   :alt: Assembled camera
   :name: fig:camera_assemble

The second part is completely up to you. You must build a mount for the camera, from whatever items you have available. We provide some guiding images that might help you, but note that you might not have similar materials available. Some guidelines for making a good mount:

* make sure it's stable and well-attached to the car. Again, in the actual race, your car might be going fast, so it is a possibility that the mount might be thrown off. Make sure you test it thoroughly;
* the car should be facing downwards, looking in front of the car. You want to be able to see what's coming and adjust your controls accordingly. How far you want to see is up to you, but make sure the camera is placed such that it can see the track and any guiding lines.

**add more figures here**

Additional resources
--------------------

You can find more resources available on the corresponding `Freescale community website page <https://community.freescale.com/docs/DOC-1014>`_.

