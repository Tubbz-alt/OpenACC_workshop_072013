Poisson FDM BMT �̐���
                                                        2006�N2��10��

���z�z�t�@�C���Ɋ܂܂�Ă�����́i3�t�@�C���j
�EhimenoBMTxpr.f(�x���`�}�[�N�{��)
�Eparam.h(���T�C�Y�p�����[�^�t�@�C��)
�Eparamset.sh(�p�����[�^�t�@�C���쐬�V�F��)


���R���p�C���Ǝ��s���@
�{�v���O������Fortran77 + MPI�ŋL�q����Ă��܂��D
���̂��߁CMPI�̃��C�u������Fortran�R���p�C�����K�v�ł��D
�܂����s����O�ɖ��T�C�Y����уv���Z�b�T����
�ݒ肷�邽�߂�paramset.sh �����s���܂��D�Ⴆ�΁C

% paramset.sh XL 4 4 4

���̗�ł� XL �T�C�Y�Ŗ��T�C�Y�̊e�������S��
���������p�����[�^���쐬���邱�ƂɂȂ�܂��D
�܂�XL�T�C�Y�̖��� 4x4x4=64 CPU �Ōv�Z����
�p�����[�^�t�@�C�����ł�������܂��D

�����āC�R���p�C������ю��s�̗�Ƃ��ẮC

% mpif77 Poisson_FEM_BMT.F 
% mpirun -np 16 ./a.out 

�̂悤�ɂȂ�܂��D�����ŁC16 �͎g�p����v���Z�b�T����\���Ă��܂��D

