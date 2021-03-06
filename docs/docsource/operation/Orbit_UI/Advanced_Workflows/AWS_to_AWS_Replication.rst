AWS-to-AWS Replication
======================

#. Create a bucket on AWS
   (https://s3.console.aws.amazon.com/s3/buckets/) with versioning
   enabled

   |image0|

#. From Orbit, open **Storage Location**, click **Add New** and enter
   information (location name, type, and type-specific options) for the AWS
   bucket you just created.

   |image1|

#. From the Multicloud Browser, create another bucket and set the new
   AWS location as its location constraint.

   If using AWS CLI, set the endpoint as the Zenko deployment, and location
   constraint as the AWS location.

#. The bucket created through Zenko appears in the drop-down menu on the
   **Set up bucket replication** dialog box.

   |image2|

#. With the AWS target now visible, enter the flow as described in `Set Up
   Replication`_.

.. _`Set Up Replication`: set_up_crr.html

.. |image0| image:: ../../Resources/Images/Orbit_Screencaps/aws_versioning_enabled.png
   :class: OneHundredPercent
.. |image1| image:: ../../Resources/Images/Orbit_Screencaps/Orbit_Add_Storage_location_AWS.png
   :class: FiftyPercent
.. |image2| image:: ../../Resources/Images/Orbit_Screencaps/Orbit_set_up_bucket_replication_pulldown.png
   :class: FiftyPercent
