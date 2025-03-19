# Exam-practice-250318
## Creating a bootable USB
[Here is the first link to how to create a bootable usb for window 10](https://www.youtube.com/watch?v=abpAPQH1Rs)

[Here is the 2nd link to how to create a bootable usb for window 11](https://www.youtube.com/watch?v=NSRCZEKDMK8)
### Steps to how to install a window
Method 1: Using Rufus (Recommended for most users)
Rufus is a popular and easy tool for creating bootable USB drives.

Download and Install Rufus:

Go to Rufus website and download the latest version.

Insert the USB Drive:

Plug your USB drive into your computer (ensure no important files are on it, as the process will erase everything on it).

Open Rufus:

Run Rufus (you don’t need to install it as it's a portable app).

Select USB Drive in Rufus:

In the Rufus window, under Device, select your USB drive from the dropdown menu.

Select Boot Selection:

For Boot selection, choose Disk or ISO image (Please select).

Click Select, then browse to find the Windows ISO file you downloaded earlier.

Partition Scheme:

For Partition scheme, select GPT (if you're using UEFI) or MBR (for legacy BIOS systems).

For File system, choose NTFS (for large file support, recommended for Windows).

Start the Process:

Click Start. You’ll be prompted with a warning that the USB drive will be formatted. Click OK to continue.

Rufus will now create a bootable Windows USB drive.

Complete:

Wait for the process to finish. Once done, your USB drive is ready to install Windows.
