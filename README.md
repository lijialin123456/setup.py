from setuptools import setup, find_packages

setup(
    name='earthquake-disaster-app',
    version='1.0',
    packages=find_packages(),
    install_requires=[
        'requests>=2.25.1',
        'numpy>=1.21.0',
        # 添加其他依赖项
    ],
    author='setup.py',
    author_email='2175880049@qq.com',
    description='A package for earthquake disaster management',
    # 添加其他元数据
)
