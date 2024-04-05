clear;
clc;
close all;

disp('Assalamualaikum')
disp('Selamat datang di mata kuliah pengolahan citra digital')
nama=input('Nama=','s');
nim=input('NIM=');


% Membaca gambar
img = imread('foto1.jpg');

% Menghitung intensitas grayscale
lightness = (img(:,:,1) + img(:,:,2) + img(:,:,3)) / 3;
average = 0.3 * img(:,:,1) + 0.59 * img(:,:,2) + 0.11 * img(:,:,3);
luminosity = 0.2126 * img(:,:,1) + 0.7152 * img(:,:,2) + 0.0722 * img(:,:,3);

% Menentukan nilai threshold
threshold = 128; % Ubah nilai ini sesuai gambar Anda

% Menghasilkan citra biner
binary = lightness > threshold;

% Menampilkan gambar
figure(131), imshow(img), title('Gambar Asli');
figure(132), imshow(lightness), title('Lightness');
figure(133), imshow(average), title('Average');
figure(231), imshow(luminosity), title('Luminosity');
figure(232), imshow(binary), title('Citra Biner');

% Menampilkan gambar asli
imshow(img), title('Gambar Asli');
