Image = imread('pout.tif');
figure;
imshow(Image); %Original image ,Figure#1
first_Dev = edge(Image, 'prewitt');
figure;
imshow(first_Dev); %First derivative ,Figure#2
second_Dev = edge(Image, 'log');
figure;
imshow(second_Dev); % Second derivative ,Figure#3
canny = edge(Image, 'canny');
figure;
imshow(canny); % Using canny algorithm ,Figure#4

